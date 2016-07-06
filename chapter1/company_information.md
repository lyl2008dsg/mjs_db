#company_information
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|UNI|loan_id|关联loan的id|int(10) unsigned|NO||
|MUL|user_id|关联user_main|int(10) unsigned|NO||
||company_background|企业背景|varchar(1500)|YES||
||business_scope|经营范围|varchar(1500)|YES||
||business_state|经营状况|varchar(1500)|YES||
||assure_id|关联assure_organization|int(10)|YES||
||assure_opinion|担保意见|varchar(1500)|YES||
||pawn|抵押物简介|varchar(1300)|YES||
||risk_measures|风控措施|varchar(1500)|YES||
||funds_use|资金用途|varchar(1500)|YES||
||repayment_source|还款来源|varchar(1500)|YES||
|
