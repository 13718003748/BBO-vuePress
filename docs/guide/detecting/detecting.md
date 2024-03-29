## isIOS
### isIOS:  `bbo.isIOS() or bbo.isIos()`
Check whether the mobile device is an IOS device.

**example:** 
```
if(bbo.isIOS()) { console.log('this is ios'); }
```

**result:** detecting is ios - false


## isAndroid 
### isAndroid:  `bbo.isAndroid()`
Check whether the mobile device is an Android device.

**example:** 
```
if(bbo.isAndroid()) { console.log('this is android'); }
```

**result:** detecting is android - false


## isiPhone  
### isiPhone :  `bbo.isiPhone()`
Check whether the mobile device is an iphone.

**example:** 
```
if(bbo.isiPhone()) { console.log('this is iphone'); }
```

**result:** detecting is iphone - false


## isIPad   
### isIPad :  `bbo.isIPad()`
Check whether the mobile device is an IPad.

**example:** 
```
if(bbo.isIPad()) { console.log('this is ipad'); }
```

**result:** detecting is ipad - false


## isMobile 
### isMobile :  `bbo.isMobile()`
Check if the current device is a mobile device.

**example:** 
```
if(bbo.isMobile()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is Mobile - false


## isPC 
### isPC :  `bbo.isPC()`
Check if the current device is a PC device.

**example:** 
```
if(bbo.isPC()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is isPC - false


## isWeixin 
### isWeixin :  `bbo.isWeixin()`
Check if the current device is Weixin device.

**example:** 
```
if(bbo.isWeixin()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is Weixin - false


## isNewsApp 
### isNewsApp :  `bbo.isNewsApp()`
Check if the current device is NewsApp device.

**example:** 
```
if(bbo.isNewsApp()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is isNewsApp - false


## isQQ 
### isQQ :  `bbo.isQQ()`
Check if the current device is QQ device.

**example:** 
```
if(bbo.isQQ()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is isQQ - false


## isTenvideo 
### isTenvideo :  `bbo.isTenvideo()`
Check if the current device is Tenvideo device.

**example:** 
```
if(bbo.isTenvideo()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is isTenvideo - false


## isIphoneXmodel 
### isIphoneXmodel :  `bbo.isIphoneXmodel()`
Check if the current device is IphoneXmodel device.

**example:** 
```
if(bbo.isIphoneXmodel()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is isIphoneXmodel - false


## mqqbrowser 
### mqqbrowser :  `bbo.mqqbrowser()`
Check if the current device is mqqbrowser device.

**example:** 
```
if(bbo.mqqbrowser()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is mqqbrowser - false


## isIE  
### isIE  :  `bbo.isIE()`
Detect the current browser is Microsoft IE.

**example:** 
```
if(bbo.isIE()) { document.querySelector('.title').style.color = '#fff'; }
```

**result:** detecting is IE browser - false


## ieVersion  
### ieVersion  :  `bbo.ieVersion() or bbo.ieVer()`
Check the IE browser version.

```
document.getElementById('info').innerText = bbo.ieVersion();
```

**result:** IE browser version - 11.1.1


## ua   
### ua   :  `bbo.ua(lower?)`
return navigator.userAgent.

**example:** 
```
console.log(bbo.ua()); 
console.log(bbo.ua('l')); 
console.log(bbo.ua('lower')); 
```

**result:** Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/78.0.3904.108 Safari/537.36