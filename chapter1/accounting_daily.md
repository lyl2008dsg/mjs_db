#accounting_daily
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|adate|记账日期|date|NO||
|PRI|catalog_id|科目编号|varchar(36)|NO||
||balance|余额|decimal(10,2)|YES||
||credit_amount|贷方发生额|decimal(10,2)|YES||
||debit_amount|借方发生额|decimal(10,2)|YES||
|
