# jquery.ua [![spm version](http://spmjs.io/badge/jquery.ua)](http://spmjs.io/package/jquery.ua)
AUTHOR WEBSITE: [http://ydr.me/](http://ydr.me/)

判断360、chrome、firefox、IE浏览器的UA、版本、外壳等信息

__IT IS [A spm package](http://spmjs.io/package/jquery.ua).__




#USAGE
```
var $ = require('jquery');
require('jquery.ua')($);


// 1. 获取ua字符串
$.ua().ua;

// 2. 设置ua字符串
$.ua('string');

// 3. 获取参数
$.ua().platform;
$.ua().browser;
$.ua().engine;

// 4. 内核判断
$.ua().isWebkit;
$.ua().isGecko;
$.ua().isTridentisTrident;

// 4. 外壳判断，与UA无关，属于静态属性
$.ua.isChrome;
$.ua.isFirefox;
$.ua.is360se;
$.ua.is360ee;
$.ua.isLiebao;
$.ua.isSougou;
$.ua.isQQ;
$.ua.ie;
$.ua.isIe;
$.ua.isIe6;
$.ua.isIe7;
$.ua.isIe8;
$.ua.isIe9;
$.ua.isIe10;
$.ua.isIe11;
```



