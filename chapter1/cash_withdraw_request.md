#cash_withdraw_request
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
||amount|提现申请金额|decimal(12,2)|NO||
|MUL|applyTime|提现申请时间|datetime|NO||
||fee|手续费|decimal(8,2)|NO||
||handleTime|处理此请求的时间|datetime|YES||
||bankCardNo|申请提现的银行卡号|varchar(25)|NO||
||bankCode|申请提现的银行卡所在银行的代码，见bank_code.sql|varchar(20)|YES||
||bankCardBranch|申请提现的银行卡的发卡行|varchar(50)|YES||
|MUL|userId|申请用户id|int(10) unsigned|NO||
||status|状态 UserDef.CASH_WITHDRAW_*|smallint(5) unsigned|NO||
||operationComment|操作注释，供后台人员使用|varchar(32)|YES||
|
