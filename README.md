# supervisor_doc
supervisor 简单配置

#supervisord.conf
```
默认的配置文件路径是/tmp   // 临时文件夹内的需要改到你自己配置的文件夹

[include]
files = /etc/supervisor/*.conf
加载脚本配置文件
```

#batch_asyn_listen.conf
```
执行的脚本配置文件

本文件搭配 Laravel 所以示例为laravel的command执行方式
 
```


