#user_modify_pwd
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|主键|int(10) unsigned|NO||
||userId|用户id|int(10)|YES||
||nickName|用户名|varchar(32)|YES||
||ip|修改ip|varchar(32)|YES||
||altermode|修改方式 1:web2:移动|int(5)|YES||
||type|1:修改密码 2：找回密码|int(5)|YES||
||oldPwd|原密码|varchar(50)|YES||
||newPwd|新密码|varchar(50)|YES||
||modifyDate|修改时间|datetime|YES||
||detail|详细描述|varchar(255)|YES||
|
