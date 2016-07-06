#redmoney_constant_cfg
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(11)|NO||
||redmoney_category_id|红包种类ID|int(11)|YES||
||type|红包类型 1注册 2邀请好友3.vip升级红包V1 4.vip升级红包V2 5.vip升级红包V3 6vip升级红包V4 7.vip升级红包V5 8.vip升级红包V6 9.vip升级红包V7 |int(2)|NO||
||days|有效期 单位：天|int(6)|NO||
||use_range|使用范围 #1#,债权转让项目使用 #2#,优选理财使用 #3#,散标项目使用|varchar(255)|YES||
||is_push|是否推送 0不推送 1推送|tinyint(1)|YES||
||is_open|是否开启|tinyint(1)|YES||
||push_way|推送方式,#1#,站内信 #2#,邮件 #3#,短信 示例：#1##2##3#|varchar(255)|YES||
|
