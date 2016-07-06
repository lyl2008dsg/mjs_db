#menu
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|id|int(10)|NO||
||createTime|创建时间|datetime|YES||
||updateTime|更新时间|datetime|YES||
||dispOrder|排序|int(10)|YES||
||level|优先级|int(10)|YES|0|
||style|类型 1 功能导航 2 功能菜单  |varchar(60)|YES||
||text|名称|varchar(60)|YES||
||url|url|varchar(60)|YES||
||parentId|父级|int(10)|YES|0|
||menuFlag||int(4)|YES||
|
