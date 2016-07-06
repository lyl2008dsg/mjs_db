#finance_apply
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(11)|NO||
||name|姓名|varchar(200)|YES||
||register_name|注册号|varchar(50)|YES||
||card_no|身份证号|varchar(50)|YES||
||phone|联系方式|varchar(20)|YES||
||city|所在城市|varchar(20)|YES||
||amount|借款金额|decimal(14,2)|YES||
||period|周期|int(10)|YES||
||loan_use|借款用途|text|YES||
||repay_source|还款来源|text|YES||
||loan_type|1:个人 2：企业|int(11)|YES||
||company_name||varchar(100)|YES||
||interest_rate|企业融资利率|decimal(4,2)|NO||
|
