### a.gamersky.com/app/下载参数说明

http://a.gamersky.com/app/?source=example

source=example 为包的版本后名称，如 :

 > gamersky_v3.6.2_WapTuiJian.apk --- http://a.gamersky.com/app/?source=WapTuiJian
 > 
 > gamersky_v3.6.2_wap.apk --- http://a.gamersky.com/app/?source=wap
 
 ##### source 目前支持的参数：wap|WapTuiJian|WapNeiRong|WapGongLue
>  http://a.gamersky.com/app/ 默认下载 gamersky_v3.6.2_wap.apk

#### FTP更新说明：
a.gamersk.com/app/ - index.html
```html
<!-- 51行 -->
<script>
var apkList = {
    wap:'//btfile.gamersky.com/app/2018/04/gamersky_v4.0.2_wap.apk',
    WapTuiJian:'//btfile.gamersky.com/app/2018/04/gamersky_v4.0.2_WapTuiJian.apk',
    WapNeiRong:'//btfile.gamersky.com/app/2018/04/gamersky_v4.0.2_WapNeiRong.apk',
    WapGongLue:'//btfile.gamersky.com/app/2018/04/gamersky_v4.0.2_WapGongLue.apk
};

...

</script>
```

a.gamersk.com/ - index.html 安卓地址
```html
···
<script>
var appLinks = {
        android:'//btfile.gamersky.com/app/2018/04/gamersky_v4.0.2_wap.apk',//安卓地址
...

</script>
```
