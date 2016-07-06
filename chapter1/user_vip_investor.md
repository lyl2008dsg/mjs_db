#user_vip_investor
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|UNI|userId|用户id，和user_main.userId关联|int(10) unsigned|NO||
||points|用户积分|decimal(16,0)|NO|0|
||marketingChannel|营销渠道|smallint(5) unsigned|NO|0|
|MUL|joinTime|加入时间|datetime|NO||
||reserveNetProfit|标志位，默认1为保留净收益；0为收益再投资|tinyint(1)|NO|1|
||interestAutoWithdraw|标志位，默认0为关闭；1为利息自动提现|tinyint(1)|NO|0|
||lockedPeriod|锁定期，单位为月|smallint(5) unsigned|NO|12|
||joinFeeRate|加入费率百分比|decimal(4,2) unsigned|NO|0.00|
||serviceFeeRate|服务费率百分比|decimal(4,2) unsigned|NO|0.00|
||redeemFeeRate|赎回费率百分比|decimal(4,2) unsigned|NO|0.00|
|
