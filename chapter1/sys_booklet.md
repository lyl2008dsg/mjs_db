#sys_booklet
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|UUID, 字典类型+编码 可以唯一标识|varchar(36)|NO||
||type|字典类型|varchar(32)|YES||
||display|字典显示名称|varchar(32)|YES||
||ordinal|序号 排序用|int(11)|YES|0|
||enabled|是否可用|bit(1)|YES||
||code||varchar(255)|YES||
||value||varchar(255)|YES||
|
