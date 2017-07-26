# parking_meter phpunit 跑通指南
>  step 1

~~~linux
把下载的activerecord/这个文件夹放到parking_meter/02-source/parkingmeter.api/usr/lib/php/pear下
~~~

> step2


在系统根目录创建文件夹
~~~js
# mkdir -p /data/conf/parking_meter/db/
~~~

> step3

把文件MySQLServerConfig.inc.php放到/data/conf/parking_meter/db/下
~~~js
# cp parking_meter/02-source/parkingmeter.config/db/dev/MySQLServerConfig.inc.php
 /data/conf/parking_meter/db/
~~~
> step3

修改MySQLServerConfig.inc.php 为你的数据库的账号·密码·端口·数据库名
