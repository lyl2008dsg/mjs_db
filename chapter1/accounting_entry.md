#accounting_entry
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|aid|分录号|varchar(36)|NO||
|PRI|catalog_id|科目编号|varchar(36)|NO||
||amount|发生额|decimal(10,2)|YES||
||symbol|借贷标识 debit credit |varchar(1)|YES||
||atime|记账时间|datetime|YES||
||staff_id|记账人ID|varchar(36)|YES||
||staff_name|记账人姓名|varchar(36)|YES||
||atype|记账类型 自动 手工|int(11)|YES||
||remark|备注|varchar(255)|YES||
||ctime||datetime|YES||
||keep_type||int(11)|YES||
||id||varchar(36)|NO||
|
