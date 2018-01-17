# Map

#如何在HTTPS 网页中引入HTTP资源： Mixed Content？#
加入下面这段代码：
<pre>
 ```JavaScript
  <meta http-equiv="Content-Security-Policy" content="upgrade-insecure-requests">
```
</pre>  
