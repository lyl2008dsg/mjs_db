#loan_investor
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|loanId|关联的loanId|int(10) unsigned|NO||
|MUL|investorUserId|关联的userId|int(10) unsigned|NO||
||investorNickname|投资昵称|varchar(64)|NO||
||lastInvestorUserId|上一个投资人id|int(10) unsigned|NO||
||lastInvestorNickname|上一个投资人昵称|varchar(64)|NO||
||investAmount|此Investor对某标的借出金额|decimal(14,2)|NO||
|MUL|investTime|投标时间|datetime|NO||
||borrowerCreditPoint|借入者信用分数|smallint(5) unsigned|NO||
||termReturnAmount|每期的回款额|decimal(14,2)|NO||
||lastTermPrincipalCompensation||decimal(14,2)|NO||
||leftTermCount|剩余还款期数|smallint(5) unsigned|NO||
||toBeCollectedPrincipal|将要回收的本金|decimal(14,2)|NO||
||toBeCollectedInterest|将要回收利息|decimal(14,2)|NO||
||collectedPrincipal|已经回收的本金|decimal(14,2)|NO||
||collectedInterest|已经回收的利息|decimal(14,2)|NO||
||nextPhasePrincipal|下一期要还本金|decimal(14,2)|NO||
||nextPhaseInterest|下一期要还利息|decimal(14,2)|NO||
||lastRepayDate|上一次还款日期|datetime|YES||
||nextRepayDate|下一个还款日期，冗余，和关联的loan_phase的对应字段一致|datetime|NO||
||autoInvest|是否自动投标|tinyint(1)|NO|0|
||status|状态值，表示此投资/债权是正常，出售中，还是其他状态。 定义见LoanDef.LOAN_INVESTOR_STATUS_*|smallint(5) unsigned|NO||
||soldPrice|销售价格，按照目前政策，是此债权价值的90%|decimal(14,2)|YES||
||soldDate|债权卖出时间|datetime|YES||
||soldPhaseNum|债权第几期卖出|smallint(5) unsigned|YES||
||overDueDays|逾期天数|smallint(5) unsigned|YES||
||overDueInterest|逾期罚息，每天更新|decimal(10,2)|YES||
||soldDiscountRate|债权交易折让率（用户设定）|decimal(5,4) unsigned|YES||
||soldCommission|债权交易手续费|decimal(10,2) unsigned|YES||
||contractNo|支付账户预授权合同号|varchar(50)|YES||
|UNI|serialNumber||varchar(80)|YES||
||inputFrom||int(5)|YES||
||red_money_id|红包ID|varchar(255)|YES||
||toBeCollectedRedmoneyInterest|将要回收的红包利息|decimal(14,2)|YES|0.00|
||collectedRedmoneyInterest|已经回收的红包利息|decimal(14,2)|YES|0.00|
|
