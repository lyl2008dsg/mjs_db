#preferred_plan
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|preferredPlanId|标编号|int(10) unsigned|NO||
|MUL|amount|总额|decimal(14,2)|NO||
||title|借款标题|varchar(64)|NO||
||description|借款描述|varchar(512)|YES||
||annualInterestRate|年化利率|decimal(4,2)|YES||
||termCount|还款周期数量|float(10,2) unsigned|NO||
||biddingAmount|目前已投标的金额|decimal(14,2)|YES|0.00|
||createTime|标建立的时间，也就是借款者填写借款金额，期限后，提交的时间|datetime|NO||
||openTime|开标时间|datetime|YES||
||openEndTime|招标结束时间，如果标开放期限是7天，则此值即openTime+7天|datetime|YES||
||fullTime|满标时间|datetime|YES||
|MUL|status|状态码，0未开始，1进行中，2已结束|smallint(5) unsigned|YES|0|
||recordNum||int(11)|YES||
||exannualInterestRate||decimal(4,2)|YES||
||minInvestAmount||decimal(14,0)|YES||
||type||int(5) unsigned|YES|1|
|
