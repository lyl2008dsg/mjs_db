#favorite
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(11)|NO||
||user_id|用户ID,每位用户最多设置5个|int(11)|YES||
|MUL|credit_id|借款等级ID|int(11)|YES||
||amount_upper|金额范围-上限|decimal(11,2)|YES||
||amount_lower|金额范围-下限|decimal(11,2)|YES||
||term_upper|期限范围-上限 单位：天|decimal(11,2)|YES||
||term_lower|期限范围-下限 单位：天|decimal(11,2)|YES||
||rate_upper|利率范围-上限|decimal(11,2)|YES||
||rate_lower|利率范围-下限|decimal(11,2)|YES||
||create_date|添加时间|datetime|NO||
||msgs_id|消息队列的UUID 例如：11111111aaaa,22222aaaa,33321111aaaa,|text|YES||
||is_push|是否推送 0不推送 1推送|tinyint(1)|YES||
||push_way|推送方式,#1#,站内信 #2#,邮件 #3#,短信 示例：#1##2##3#|varchar(255)|YES||
|
