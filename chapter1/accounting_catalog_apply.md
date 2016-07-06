#accounting_catalog_apply
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|trade_id|交易类别见字典, 如:充值,提现|varchar(36)|NO||
|PRI|name|参数名称|varchar(36)|NO||
||catalog_id|科目编号|varchar(36)|YES||
||symbol|借贷标识 debit credit |varchar(1)|YES||
||note||varchar(100)|YES||
|
