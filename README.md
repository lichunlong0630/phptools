# phptools
仅用于学习和研究
* 1）基于Thinkphp6 的 Auth，基础来源于5ini99的think-auth，略做修改。
* 2）基于Thinkphp6 的 Jump，基础来源于liliuwei/thinkphp-jump，略做修改。
## 安装
* 1）安装主框架
~~~php
composer create-project topthink/think tp 6.0.*
//cmd 切换至tp目录，安装一下类库
~~~
* 2）安装权限管理和Jump插件类库
~~~php
composer require lichunlong0630/phptools
~~~
* 3）安装View引擎
~~~php
composer require topthink/think-view
~~~
* 4）安装验证码类库
~~~php
composer require topthink/think-captcha
~~~
* 5）安装日志类库
~~~php
composer require topthink/think-log
~~~
* 6）安装Excel处理类库
~~~php
composer require phpoffice/phpspreadsheet
~~~
