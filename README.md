I18NC-KEY-TRIM
==================


[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Coveralls][coveralls-image]][coveralls-url]
[![NPM License][license-image]][npm-url]

# Install
```
npm install i18nc-key-trim
```

# Useage

```javascript
var i18nc = require('i18nc');
require('i18nc-key-trim')(i18nc);

i18nc('var str="<span> 中文 词典 </span>"', {pluginEnabled: {keyTrim: true}});
console.log(i18nc.code);	// var str='<span> '+I18N('中文 词典')+' </span>';
```


[npm-image]: http://img.shields.io/npm/v/i18nc-key-trim.svg
[downloads-image]: http://img.shields.io/npm/dm/i18nc-key-trim.svg
[npm-url]: https://www.npmjs.org/package/i18nc-key-trim
[travis-image]: http://img.shields.io/travis/Bacra/node-i18nc-key-trim/master.svg?label=linux
[travis-url]: https://travis-ci.org/Bacra/node-i18nc-key-trim
[coveralls-image]: https://img.shields.io/coveralls/Bacra/node-i18nc-key-trim.svg
[coveralls-url]: https://coveralls.io/github/Bacra/node-i18nc-key-trim
[license-image]: http://img.shields.io/npm/l/i18nc-key-trim.svg
