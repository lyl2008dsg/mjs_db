#accounting_catalog
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|科目编号|varchar(36)|NO||
||type_id|科目类别见字典 资产 负债 损益 所有者权益|varchar(36)|YES||
||level|科目所属层级|int(11)|YES||
||name|科目名称|varchar(36)|YES||
||symbol|借贷标识/余额方向 debit credit |varchar(1)|YES||
||ordinal|序号|int(11)|YES||
||remark|备注|varchar(255)|YES||
||parent_id|上级科目编号|varchar(36)|YES||
||number||varchar(30)|YES||
||balanceable||bit(1)|YES||
||enable||tinyint(1)|YES||
|
