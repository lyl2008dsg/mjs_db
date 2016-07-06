#user_statistic
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|UNI|userId|用户id，和user_main.userId关联|int(10) unsigned|NO||
||totalCharge|总共充值金额|decimal(14,2)|NO|0.00|
||totalWithdraw|总共提现金额|decimal(14,2)|NO|0.00|
||totalAssert|总共资产|decimal(14,2)|NO|0.00|
||totalEarnedInterest|总共赚取利息|decimal(14,2)|NO|0.00|
||totalEarnedPunitiveInterest|总共赚取罚息|decimal(14,2)|NO|0.00|
||WeightedRateOfReturn|加权平均收益率|decimal(4,2)|NO|0.00|
||investCount|借出笔数|int(10) unsigned|NO|0|
||totalInvestAmout|总共借出金额|decimal(14,2)|NO|0.00|
||investAmoutInThisMonth|本月借出金额合计|decimal(14,2)|NO|0.00|
||returnedAmountInThisMonth|本月回收金额合计|decimal(14,2)|NO|0.00|
||toCollectPrincipal|待收本金|decimal(14,2)|NO|0.00|
||toCollectInterest|待收利息|decimal(14,2)|NO|0.00|
||totalReturnedPrincipal|总回收本金|decimal(14,2)|NO|0.00|
||totalPlatformPayed|总垫付金额|decimal(14,2)|NO|0.00|
||boughtCreditRights|总买入债权|decimal(14,2)|NO|0.00|
||soldCreditRights|总卖出债权|decimal(14,2)|NO|0.00|
||requestLoanCount|发布借款笔数|smallint(6)|NO|0|
||permittedLoanCount|成功借款笔数|smallint(6)|NO|0|
||finishedLoanCount|还清笔数|smallint(6)|NO|0|
||overDueCount|还清笔数|smallint(6)|NO|0|
||badLoanCount|严重逾期次数|smallint(6)|NO|0|
||totalPermittedAmount|总共申请金额|decimal(14,2)|NO|0.00|
||totalToRepayAmount|总共待还金额|decimal(14,2)|NO|0.00|
||totalOverDueAmount|总共逾期金额|decimal(14,2)|NO|0.00|
||actualLoanAmount|实到借款额|decimal(14,2)|NO|0.00|
||serviceFees|服务费|decimal(14,2)|NO|0.00|
||riskMargin|风险保证金|decimal(14,2)|NO|0.00|
||alreadyPayInterest|已交罚息|decimal(14,2)|NO|0.00|
||totalInterest|总应付利息|decimal(14,2)|NO|0.00|
||alreadyRepayment|已还金额|decimal(14,2)|NO|0.00|
||residualRepayment|剩余应还款|decimal(14,2)|NO|0.00|
||totalRepaiedPrincipal|总已还本金|decimal(14,2)|NO|0.00|
||totalRepaiedInterest|总已还利息|decimal(14,2)|NO|0.00|
||boughtCreditRightsCount|总买入债权笔数|int(10) unsigned|NO|0|
||soldCreditRightsCount|总卖出债权笔数|int(10) unsigned|NO|0|
||boughtCreditRightsPaidInterest|买入债权已付利息|decimal(14,2)|NO|0.00|
||boughtCreditRightsEarnedDiscount|买入债权已赚本金折让|decimal(14,2)|NO|0.00|
||soldCreditRightsEarnedInterest|卖出债权已赚利息|decimal(14,2)|NO|0.00|
||soldCreditRightsPaidDiscount|卖出债权已付本金折让|decimal(14,2)|NO|0.00|
||commissionFees|投资人手续费|decimal(14,2)|NO|0.00|
||activityBonus|推广活动收入|decimal(14,2)|NO|0.00|
||reward_money|奖励金额|decimal(20,2)|YES||
||toCollectRedmoneyInterest|红包待收利息|decimal(14,2)|YES|0.00|
||totalEarnedRedmoneyInterest|总共赚取红包利息|decimal(14,2)|YES|0.00|
|
