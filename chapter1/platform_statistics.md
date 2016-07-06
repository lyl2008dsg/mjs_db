#platform_statistics
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|主键|int(10) unsigned|NO||
||startTime|统计开始时间|datetime|NO||
||endTime|统计结束时间|datetime|NO||
||transitCash|资金中转账户（id=1）现金余额|decimal(14,2)|NO||
||riskCash|风险保证金账户（id=2）现金余额|decimal(14,2)|NO||
||incomeCash|平台收入账户（id=3）现金余额|decimal(14,2)|NO||
||investorCashSum|普通投资人用户（id>10000 and role=1）未冻结现金余额总和|decimal(14,2)|NO||
||borrowerCashSum|普通借款人用户（id>10000 and role=2）未冻结现金余额总和|decimal(14,2)|NO||
||investorFrozenWithdrawCashSum|普通投资人提现冻结总和|decimal(14,2)|NO||
||borrowerFrozenWithdrawCashSum|普通借款人提现冻结总和|decimal(14,2)|NO||
||investorFronzenBiddingCashSum|普通投资人投标冻结总和|decimal(14,2)|NO||
||userLoginCount|用户登录数|int(11)|YES|0|
||investorUserNum|截止当日的投资用户人数|int(10)|YES|0|
|
