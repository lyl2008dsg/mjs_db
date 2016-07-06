#staff
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|员工id|int(10) unsigned|NO||
|MUL|departmentId|部门id|int(10) unsigned|YES||
|MUL|userRoleId|用户角色id|int(10) unsigned|YES||
|UNI|userId|用户uid|int(10) unsigned|YES||
||passwd|密码|varchar(50)|YES||
||staffName|员工名称|varchar(50)|YES||
||sex|0 男 1 女|smallint(5) unsigned|YES||
||realname||varchar(50)|YES||
||email|电子邮件|varchar(32)|YES||
||mobile|移动电话|varchar(11)|YES||
||phone|固定电话|varchar(50)|YES||
||age|年龄|int(10) unsigned|YES||
||birthday|生日|varchar(10)|YES||
||idCard|身份证号|varchar(20)|YES||
||qq|QQ号码|varchar(12)|YES||
||lowest|最低审批额度|int(10) unsigned|YES||
||highest|最高审批额度|int(10) unsigned|YES||
||firstTaskNo|当前初审任务数|int(10) unsigned|NO|0|
||secondTaskNo|当前复审任务数|int(10) unsigned|NO|0|
||x509SKeyId|X.509 数字证书使用者密钥标识符|varchar(40)|YES||
|
