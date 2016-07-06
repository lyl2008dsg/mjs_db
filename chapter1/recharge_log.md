#recharge_log
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|rechargeLogId||int(10) unsigned|NO||
||amount|充值金额|decimal(14,2)|NO||
||payId|支付id|varchar(64)|NO||
||rechargeTime|支付时间|datetime|NO||
||payType|支付类型|smallint(5) unsigned|NO||
|MUL|userId|支付者id|int(10) unsigned|NO||
||recharge_fee|充值费用|decimal(10,2)|NO||
||reserve_fee_balance|预留充值费用余额|decimal(10,2)|YES||
||flag|默认是0未成功，1是成功|tinyint(1)|NO|0|
|
