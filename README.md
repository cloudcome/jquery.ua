# jquery.ua

---

[![spm version](http://spmjs.io/badge/jquery.ua)](http://spmjs.io/package/jquery.ua)

jquery.ua 插件判断360、chrome、firefox、IE浏览器的UA、版本、外壳等信息

---

## Install

```
$ spm install jquery.ua --save
```

## Usage

It is very easy to use this module.

```js
var $ = require('jquery');
require('jquery.ua')($);
```


## Api

### set ua string
```js
// default is navigator.userAgent
$.ua();
$.ua('string');
```

### get ua string
```js
$.ua().ua;
```

### get ua params
```js
$.ua().platform;
$.ua().browser;
$.ua().engine;

$.ua().isWebkit;
$.ua().isGecko;
$.ua().isTridentisTrident;
```


### get brower params
```js
// 是否为原版 chrome
$.ua.isChrome;

// 是否为 firefox
$.ua.isFirefox;

// 是否为 360 安全浏览器
$.ua.is360se;

// 是否为 360 极速浏览器
$.ua.is360ee;

// 是否为猎豹浏览器
$.ua.isLiebao;

// 是否为搜狗浏览器
$.ua.isSougou;

// 是否为 QQ 浏览器
$.ua.isQQ;

// IE 浏览器版本值
$.ua.ie;

// 是否为 IE 浏览器
$.ua.isIe;

// 是否为 IE6 浏览器
$.ua.isIe6;

// 是否为 IE7 浏览器
$.ua.isIe7;

// 是否为 IE8 浏览器
$.ua.isIe8;

// 是否为 IE9 浏览器
$.ua.isIe9;

// 是否为 IE10 浏览器
$.ua.isIe10;

// 是否为 IE11 浏览器
$.ua.isIe11;
```


