#user_register_temp
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
||email|邮件|varchar(32)|NO||
||nickName|用户昵称|varchar(32)|NO||
||passwd|密码|varchar(32)|NO||
||registerTime|注册时间|datetime|NO||
||roles|角色，参见com.zkbc.core.consts.user.UserRolesType|smallint(5) unsigned|YES||
||question|安全问题|varchar(255)|NO||
||answer|安全问题答案|varchar(255)|NO||
||weiboUId|新浪微博uid|varchar(64)|YES||
||weiboAccessToken|新浪微博AccessToken|varchar(64)|YES||
||qqUId|腾讯uid|varchar(64)|YES||
||qqAccessToken|腾讯AccessToken|varchar(64)|YES||
||origin|借款用户的渠道|smallint(6)|YES||
||staffId|所属客户经理|int(10) unsigned|YES||
|
