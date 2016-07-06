#user_autoinvest_profile
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|记录ID号|int(10) unsigned|NO||
|UNI|userId|用户ID，与user_main表关联|int(10) unsigned|NO||
||autoInvestEnableStatus|是否开启自动投标|smallint(6)|NO|900|
||annualInterestRateMin|自动投标年化利率下限|decimal(4,2)|NO|10.00|
||annualInterestRateMax|自动投标年化利率上限|decimal(4,2)|NO|24.00|
||repayTermMin|还款周期下限|smallint(5) unsigned|NO|6|
||repayTermMax|还款周期上限|smallint(5) unsigned|NO|36|
||creditLevel|允许投标的信用等级（保存字符串）|varchar(100)|YES||
||creditLevelMin|投标信用等级下限,AA,A,B,C,D,HR,默认值为A的下限250|smallint(6)|NO|250|
||creditLevelMax|投标信用等级上限,AA,A,B,C,D,HR,默认值为AA的上限800|smallint(6)|NO|800|
||amountPerInvest|每笔投标额度|decimal(14,2)|NO|200.00|
||reservedCash|帐户保留可用余额|decimal(14,2)|NO|0.00|
||reserveNetProfit|保留净收益|smallint(6)|YES|0|
||temporarilyDisabled|标志位，因余额不足被临时禁用|tinyint(1)|YES|0|
||bestAfford|标志位，单次集中投标|tinyint(1)|YES|0|
||fullTopPriority|标志位，优先满标|tinyint(1)|YES|0|
||lastBid|上次自动投标时间戳，用于排队|bigint(20) unsigned|NO|0|
||createTime|创建自动投标记录时间|datetime|NO||
||lastUpdate|上次更新时间|timestamp|NO|CURRENT_TIMESTAMP|
|
