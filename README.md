# cordova-plugin-tencent-share


## Using the plugin

Install plugin
ionic plugin add https://github.com/yyqangular1/cordova-plugin-tencent-share-master.git

Example -share to qq friend
```javascript
TencentShare.qqShare({
    "appid": "222222",
    "title": "好班（买家版）",
    "summary": "好班，一个专注于教育辅导的App",
    "image_url": "http://static.xuexiba.com/html_v3/images/w_logo.png",
    "target_url": "http://www.xuexiba.com"
}, function() {
      console.log("ok");
}, function() {
    console.log("error");
});
```
Example -share to qzone 
```javascript
TencentShare.qzoneShare({
    "appid": "222222",
    "title": "好班（买家版）",
    "summary": "好班，一个专注于教育辅导的App",
    "image_url": "http://static.xuexiba.com/html_v3/images/w_logo.png",
    "target_url": "http://www.xuexiba.com"
}, function() {
      console.log("ok");
}, function() {
    console.log("error");
});
```
