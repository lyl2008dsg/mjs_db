#preferred_plan_investor
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|preferredPlanId|关联的loanId|int(10) unsigned|NO||
|MUL|investorUserId|关联的userId|int(10) unsigned|NO||
||investorNickname||varchar(64)|NO||
||investAmount|此Investor对某标的借出金额|decimal(14,2)|NO||
|MUL|investTime|投标时间|datetime|NO||
||status|状态值，0表示正常状态。1表示提前回收利息，2已经完成|smallint(5) unsigned|YES|0|
||collectedPrincipal|已经回收的本金|decimal(14,2)|YES||
||collectedInterest|已经回收的利息|decimal(14,2)|YES||
||toBecollectedInterestTime|预计提前回收利息的时间|date|YES||
||collectedAmountTime|回收完本息的时间|date|YES||
||toBecollectedAmountTime|预计回收本息的时间collectedInterestTime|date|YES||
|
