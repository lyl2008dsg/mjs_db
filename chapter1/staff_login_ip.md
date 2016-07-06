#staff_login_ip
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|ipId||int(10) unsigned|NO||
|MUL|userId||int(10) unsigned|NO||
||loginIP||varchar(32)|YES||
||browserType|浏览器类型，用数字定义各种浏览器|smallint(5) unsigned|NO||
||osType|操作系统类型，用数字定义|smallint(5) unsigned|NO||
||loginAddress||varchar(64)|NO||
||loginTime|登录时间|datetime|NO||
|
