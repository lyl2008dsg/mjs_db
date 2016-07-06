#disclosuer_data
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|id|int(10)|NO||
||title|数据名称|varchar(32)|YES||
||dataType|数据类型|varchar(2)|YES||
||data|数据内容|decimal(18,2)|YES||
||common|说明|varchar(32)|YES||
||isShow|是否展示（0展示1否）|int(2)|YES|0|
||isAdaptable|是否自动修改（0是1否）|int(2)|YES|0|
||staffId|操作人员id|int(10)|YES||
||updateTime|修改时间|datetime|YES||
|
