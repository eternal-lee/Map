# Map

### 如何在HTTPS 网页中引入HTTP资源： Mixed Content？
#https 引用http时才引用下面这段代码#
#加入下面这段代码：#
<pre>
 ```
   < meta http-equiv="Content-Security-Policy" content="upgrade-insecure-requests" />
```
</pre>  
