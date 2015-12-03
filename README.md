# linguist-data

[linguist's](https://github.com/github/linguist) data in JSON format, namely [languages.yml](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml), [documentation.yml](https://github.com/github/linguist/blob/master/lib/linguist/documentation.yml), [vendor.yml](https://github.com/github/linguist/blob/master/lib/linguist/vendor.yml) and [popular.yml](https://github.com/github/linguist/blob/master/lib/linguist/popular.yml).

## usage

```js
var data = require('linguist-data');
console.log(data);
```

.. or load what you want:

```js
var langs = require('linguist-data/languages.json');
var docs = require('linguist-data/documentation.json');
var vendor = require('linguist-data/vendor.json');
var popular = require('linguist-data/popular.json');
```

## build

The command below will regenerate all json data files.

```
npm run build
```

## license

[MIT](http://alessioalex.mit-license.org/)

`linguist` license:

```
Copyright (c) 2011-2015 GitHub, Inc.

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
```
