# Ruffle Embedded
For copy and paste:

```html
<script src="https://opcysss.github.io/opcysss-Ruffle-Embedded/ruffle/ruffle.js"></script>
<div class="swf"dir="ltr" style="text-align: left;" trbidi="on">
        <embed height="480" pluginspage="http://www.macromedia.com/go/getflashplayer" src="INSERT SWF FILE HERE" type="application/x-shockwave-flash" width="620"></embed>
</div>
```

version1
```html
<div style="position: relative; width: 100%; height: 0; overflow: hidden; padding-bottom: 56.26%;"> /* 16:9 = 56.26, 3:4 = 75% */
<div class="swf"dir="ltr" style="text-align: left; position: absolute; top: 0; left: 0; width: 100%; height: 100%;" trbidi="on">
        <embed height="100%" pluginspage="http://www.macromedia.com/go/getflashplayer" src="INSERT SWF FILE HERE" type="application/x-shockwave-flash" width="100%"></embed>
</div>
</div>
```

version2
```html
<style type="text/css">
   .gd__aspect-ratio-box {
       position: relative;
       overflow: hidden;
       height: 0;
       padding-top: 75%;
   }
   .gd__aspect-ratio-box iframe {
       position: absolute;
       top: 0;
       left: 0;
       width: 100%;
       height: 100%;
       border-radius: 2px;
   }
</style>
<div class="gd__aspect-ratio-box">
<div class="swf"dir="ltr" style="text-align: left; position: absolute; top: 0; left: 0; width: 100%; height: 100%;" trbidi="on">
<embed height="100%" pluginspage="http://www.macromedia.com/go/getflashplayer" src="INSERT SWF FILE HERE" width="100%"></embed>
</div>
```
