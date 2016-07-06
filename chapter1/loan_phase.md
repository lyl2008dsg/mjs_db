#loan_phase
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|loanId|loanID, 与loan表的loanId关联|int(10) unsigned|NO||
|MUL|borrowerId|借款人userid|int(10) unsigned|NO||
||plannedTermAmount|还款计划中，本期应还本息|decimal(14,2)|NO||
||plannedTermInterest|还款计划中，本期应还利息|decimal(14,2)|NO||
||plannedTermPrincipal|还款计划中，本期应还本金|decimal(14,2)|NO||
||transactionFee|手续费|decimal(14,2)|NO||
||termRemainingPrincipal|本期还款结束后，剩余未还本金|decimal(14,2)|NO||
|MUL|dueDate|截止日期|datetime|NO||
|MUL|phaseNumber|期数，第一期是1，第二期是2，以此类推|smallint(5) unsigned|NO||
||isRepaid|是否已还款|tinyint(1)|NO||
||repayDate|真正还款时间|datetime|YES||
||repaidAmount|已还本息|decimal(14,2)|YES||
||repaidPrincipal|已还本金|decimal(14,2)|YES||
||repaidInterest|已还利息|decimal(10,2)|YES||
||overDueDays|逾期天数。若本期逾期，则每晚扫描时会更新此值|smallint(5) unsigned|YES||
||overDueFee|应付逾期费用|decimal(8,2)|YES||
||overDueInterest|应付罚息|decimal(8,2)|YES||
||remindedStatus|提醒状态码|smallint(5) unsigned|NO||
||loanPhaseStatus||int(11)|YES||
||redMoneyInterestRepaid|红包利息是否发放(0:未发放；1：已发放;2 : 处理中)|tinyint(1)|YES|0|
||guarateenFees|本期应收担保费|decimal(14,2)|YES|0.00|
||invPlannedTermInterest|本期应还投资人的利息|decimal(14,2)|YES|0.00|
|
