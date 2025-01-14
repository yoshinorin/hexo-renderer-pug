# hexo-renderer-pug

[![Build Status](https://img.shields.io/github/workflow/status/hexojs/hexo-renderer-pug/Linter)](https://github.com/hexojs/hexo-renderer-pug/actions/workflows/linter.yml)
[![NPM version](https://badge.fury.io/js/hexo-renderer-pug.svg)](https://www.npmjs.com/package/hexo-renderer-pug)
[![Coverage Status](https://img.shields.io/coveralls/hexojs/hexo-renderer-pug.svg)](https://coveralls.io/r/hexojs/hexo-renderer-pug?branch=master) 

Add support for [Pug].

## Install

``` bash
$ npm install hexo-renderer-pug --save
```

## Config
PugJS [options](https://pugjs.org/api/reference.html#options) are supported. These are the options passed into [compile()](https://pugjs.org/api/reference.html#pugcompilesource-options).

Create a `pug.config.js` in your project root:

```js
module.exports = {
  compile: {  // Passed to compile().
    basedir: process.cwd(),
    // ...Other options.
  }
  // No other methods are supported for now.
}
```

[Pug]: http://pugjs.org/
