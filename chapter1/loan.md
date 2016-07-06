#loan
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|loanId|标编号|int(10) unsigned|NO||
|MUL|amount|总额|decimal(14,2)|NO||
||title|借款标题|varchar(64)|NO||
|MUL|borrowerId|借款人userid|int(10) unsigned|NO||
||borrowerNickname|借入者昵称|varchar(32)|NO||
||borrowType|借款用途，定义见LoanDef.BORROW_TYPE|varchar(64)|NO||
||description|借款描述|varchar(1512)|NO||
||annualInterestRate|年化利率|decimal(4,2)|YES||
||maxAnnualInterestRate|年化利率区间上限|decimal(4,2)|YES||
||minAnnualInterestRate|年化利率区间下限|decimal(4,2)|YES||
||termCount|还款周期数量，此字段和termUnit共同描述一个标的周期|smallint(5) unsigned|NO||
||termUnit|还款周期单位，见com.zkbc.core.consts.LoanDef|smallint(5) unsigned|NO||
||minInvestUnit|最小流转单位|int(10) unsigned|YES||
||nextRepayDate|下一个还款日期，冗余|datetime|YES||
||repayedTermCount||smallint(5) unsigned|YES|0|
||biddingAmount|目前已投标的金额|decimal(14,2)|NO|0.00|
||repayType|还款方式。目前此字段无实际作用，暂规定其值与ProductId一致|smallint(5) unsigned|NO|0|
||createTime|标建立的时间，也就是借款者填写借款金额，期限后，提交的时间|datetime|NO||
||submitTime|标提交给审核的时间|datetime|YES||
||openTime|开标时间|datetime|YES||
||openEndTime|招标结束时间，如果标开放期限是7天，则此值即openTime+7天|datetime|YES||
||fullTime|满标时间|datetime|YES||
||releaseTime|放标时间|datetime|YES||
||endTime|最后一期还款时间|datetime|YES||
||overDued|是否逾期过|tinyint(1)|YES||
||viewCount|被浏览的次数|int(10) unsigned|NO|0|
||recommendWeight|推荐权重：1立即即成为推荐标 2到开始投标时间后显示到首页 0不显示在首页|smallint(5) unsigned|YES||
|MUL|status|状态码，重要|smallint(5) unsigned|NO|0|
||startFeeRate|开始的一次性费用百分比|decimal(4,2)|YES||
||monthFeeRate|每月费用百分比|decimal(4,2)|NO||
||interestFeeRate|利息扣除百分比|decimal(4,2)|YES||
||albumCapacity|标相册容量，单位：MB。此标下所有照片的size加起来不能大于此|smallint(5) unsigned|NO|20|
||auditorId|当前此标的审贷员的id，对应staff表的staffId|int(10) unsigned|YES||
||loanPortraitId|标头像图片的id|int(10) unsigned|YES||
||loanPortraitPath|标头像图片的路径|varchar(64)|YES||
||productId|产品id，参考com.zkbc.core.consts.LoanDef.ProductId|smallint(5) unsigned|NO||
||contractNo|合同编号|varchar(32)|YES||
||dealStatus|用户处理结果：0未处理 ，1、同意 ，2、拒绝 |smallint(5) unsigned|YES|0|
||loanCode||varchar(32)|YES||
||totalFee||decimal(14,2)|YES||
||monthMoney||decimal(14,2)|YES||
||loanType|类型 1-个人标 2- 企业标|int(2)|YES||
||loanAmount|金额|decimal(20,0)|YES||
||beginAmount|起投金额|decimal(20,0)|YES||
||increaseAmount|递增金额|decimal(20,2)|YES||
||loanProductId||int(11)|YES||
||creditDegree|信用等级|varchar(10)|YES||
||assureId|担保公司Id|int(11)|YES||
||recordnum||int(11)|YES||
||inputFrom||int(5)|YES|1|
||limit_money|单笔投资限额  0为无上限|decimal(20,2)|YES||
||loan_classify|把标进行分类：1新手标，2优选理财，3散标|int(2)|YES||
||redMoney||varchar(1)|YES||
||isTransfer||varchar(1)|YES||
||transferTime||varchar(4)|YES||
||killRes|流标时标记流标原因|varchar(500)|YES||
||stopTime||datetime|YES||
||rendMold|此标可显示于那些用户类型|varchar(20)|YES|1|
||isWay|用于标注此标的可用哪些优惠|varchar(10)|YES||
||investorcontract|投资合同|varchar(50)|YES||
||debtcontract||varchar(50)|YES||
||mortgageType|抵押类型，1=房抵押，2＝车抵押，null＝无抵押|varchar(1)|YES||
||yearradix|天标的计算基线是360到366之间|int(3)|YES|360|
||valueDate|起息日|datetime|YES||
||ceaseDate|止息日|datetime|YES||
||arrivalDate|到账日|datetime|YES||
||payType|付费方式1放款时支付手续费,2还款时支付手续费|int(11)|YES|1|
||guarateenRate|担保费率|decimal(20,2)|YES||
||loanLevel|标的等级，1第三方担保，2银行存管|int(1)|YES||
||financingRate|融资利率|decimal(20,2)|YES||
||interestDays|年化益率基数|int(3)|YES|365|
||interestPrinciple|1算头不算尾、2不算头算尾、12算头算尾、0不算尾不算头|int(2)|YES||
||feemode|手续费担保费的收取模式 0:先收放款时收1:后收还款时收分期收|smallint(1)|YES|0|
||arrivalDay|T+X到账日即 止息日后几天要还款|smallint(2)|YES|0|
||monthCount|每期包含的月数|decimal(3,0)|YES|0|
||ceaseType|0不固定起息日,1固定起息日|int(1)|YES|0|
||startInterestDay|不固定起息日的 满标日+X开始起息|int(5)|YES||
||unfixedValueDays|不固定起息日的 满标日+X开始起息|int(5)|YES||
||salesRate|促销利率|decimal(5,2)|YES|0.00|
||projectId|项目id|int(10)|YES||
|
