#preferred_plan_investor_credit
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(11)|NO||
||pInvestorId||int(11)|YES||
||borrowerName||varchar(40)|YES||
||borrowerIdCardNo||varchar(19)|YES||
||creditValue|本次转让债权价值|decimal(14,2)|YES||
||borrowerWork|借款人职业情况
借款人职业情况
|varchar(50)|YES||
||loanUse|借款人借款用途|varchar(50)|YES||
||repayStarDate|还款起始日期|date|YES||
||repayTerms|还款期限（月）|int(11)|YES||
||remainTerms|剩余还款月数|int(11)|YES||
||annualInterestRate|预期债权收益率（年化）|decimal(4,2)|YES||
||status|0-历史，1-最新|int(11)|YES||
|
