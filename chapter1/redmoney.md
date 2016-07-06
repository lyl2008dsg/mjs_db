#redmoney
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|uuid|varchar(100)|NO||
||user_id|用户ID|int(11)|YES||
||amount|红包金额|decimal(11,2)|NO||
||recieve_date|普通红包：获得时间 定时红包：定时时间|datetime|NO||
||use_date|使用时间,什么时间被使用|datetime|YES||
||_mark|备注|varchar(255)|YES||
||_name|红包名称|varchar(255)|YES||
||start_date|生效时间|datetime|NO||
||end_date|过期时间|datetime|NO||
||use_range|使用范围 #1#,债权转让项目使用 #2#,优选理财使用 #3#,散标项目使用|varchar(255)|YES||
||requirement|使用要求,最低投资金额|decimal(11,2)|YES||
||source|来源 1注册，2邀请好友,3定时红包|int(2)|YES||
||_status|状态 20未使用,30已使用,40已过期|int(5)|NO|10|
||type|红包类型 0普通红包 1定时红包|int(2)|YES|0|
||users_id|推送使用，发放对象,用户的ID，例如：10001,10002,1003;-1代表全部用户|text|YES||
||msgs_id|消息队列的UUID 例如：11111111aaaa,22222aaaa,33321111aaaa,|text|YES||
||is_push|是否推送 0不推送 1推送|tinyint(1)|YES||
||is_pushed|是否已经推送 0未推送 1已经推送（不允许修改），扫描器每隔10分钟扫描一次这个表查询未推送的红包并且is_push=1|tinyint(1)|YES|0|
||push_way|推送方式,#1#,站内信 #2#,邮件 #3#,短信 示例：#1##2##3#|varchar(255)|YES||
||source_id|红包来源ID，可以存放定时红包ID|varchar(255)|YES||
||invited_info_id|invited_info的ID|int(11)|YES||
||way|������ࣺ0.����ȯ1.��Ϣȯ2.�����|int(2)|YES||
|
