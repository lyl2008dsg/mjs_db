#user_main_deleting
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|userId|用户id|int(10) unsigned|NO||
|UNI|email|邮件，要求唯一|varchar(255)|YES||
|UNI|nickName|用户昵称，要求唯一|varchar(32)|NO||
||realName|真实姓名|varchar(255)|YES||
||idCardNo|身份证号|varchar(255)|YES||
||passwd|密码|varchar(50)|NO||
||payPassword|支付密码|varchar(50)|NO||
||mobile|已绑定的手机号码，不要求唯一|varchar(255)|YES||
||city|所在城市|varchar(16)|YES||
||registerTime|注册时间|datetime|NO||
||roles|角色，参见com.zkbc.core.consts.user.UserRolesType|smallint(5) unsigned|YES||
||cash|可用现金余额  这条记录中的值才是用户真正可用的钱|decimal(14,2)|NO|0.00|
||frozenWithDrawCash|已冻结的提现中现金|decimal(14,2)|NO|0.00|
||frozenBiddingCash|已冻结的投标中现金|decimal(14,2)|NO|0.00|
||idVerifyLimit|国政通验证次数，每次验证减1，默认每人最多验证3次|smallint(5) unsigned|NO|3|
||portrait|头像id|int(10) unsigned|YES||
||status|用户状态。用数值型的好处是今后可以扩充定义，参见com.zkbc.core.consts.user.UserStatusType|smallint(5) unsigned|NO|0|
||forbidStatus|禁止状态。参见com.zkbc.core.consts.user.UserForbidStatusType|smallint(5) unsigned|NO|0|
||albumCapacity|个人相册容量，单位：MB。用户所有的userpic加起来不能大于此数值|smallint(5) unsigned|NO|50|
||securityLevel|安全等级|smallint(5) unsigned|NO|0|
||weiboUId|新浪微博uid|varchar(64)|YES||
||weiboAccessToken|新浪微博AccessToken|varchar(64)|YES||
||qqUId|腾讯uid|varchar(64)|YES||
||qqAccessToken|腾讯AccessToken|varchar(64)|YES||
||origin|借款用户的渠道|smallint(6)|YES||
||staffId|所属客户经理|int(10) unsigned|YES||
||userCode||varchar(32)|YES||
||referee|推荐人，存储推荐人用户名|varchar(32)|YES||
||nickNameSJ|昵称手机端用|varchar(100)|YES||
||vipGradeId|VIP等级|int(10) unsigned|YES||
||moldId|关联用户类型表id|int(10)|YES|1|
||creditnum||int(10)|YES||
||blacklist||varchar(20)|YES|0|
||storeId|关联stores（门店表）id|int(11)|YES||
||userCodeTime||datetime|YES||
||currentStatus|查看类CommonDef中 USER_ENTERPRISE_STATUS的定义|int(10)|YES|0|
||isAutoPayment|2 为开启中  0为：关闭中  默认为0|int(10)|YES|0|
|
