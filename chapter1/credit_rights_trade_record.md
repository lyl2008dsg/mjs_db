#credit_rights_trade_record
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|loanId|标编号，和loan.loanid关联|int(10) unsigned|NO||
|MUL|loanInvestId|债权id，和loan_investor.id关联|int(10) unsigned|NO||
|MUL|sellerUserId|出售者的userid|int(10) unsigned|NO||
|MUL|buyerUserId|买入者的userid|int(10) unsigned|NO||
||tradeTime|债权交易时间|datetime|NO||
||tradePrice|债权交易价格|decimal(14,2)|NO||
||tradePhase|债权交易期数，若为0则需要调用接口计算得出|smallint(5) unsigned|NO|0|
||tradeAmount|债权交易数额，不能超过原loan_investor.investAmount|decimal(14,2)|YES||
||tradeDiscountRate|债权交易折让率|decimal(5,4) unsigned|NO|0.9500|
||tradeCommissionFee|债权交易手续费，向出售方扣收|decimal(10,2) unsigned|NO|0.00|
|MUL|correlativeLoanInvestorId|关联投资项Id，若发生债权拆卖则非空且tradeAmount非空|int(10) unsigned|YES||
|
