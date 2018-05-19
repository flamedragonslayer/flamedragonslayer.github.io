# http://flamedragonslayer.github.io

请注意，这里设置的CNAME文件不能有任何文件格式，之前就是因为将其设为txt，导致域名与IP一直匹配不上。

如果想实现点击某个元素来跳转页面的话，记得在click监听器的function里写window.location.href时，在网址前加上http://，如"http://www.baidu.com"，否则就会出bug。