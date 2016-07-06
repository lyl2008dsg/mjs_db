#score_user
* 用户积分对照表
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|Id||int(10)|NO||
|MUL|userId|积分持有用户|int(10) unsigned|NO|0|
||usedPoints|可用积分|int(10)|YES|0|
||freezePoints|冻结积分|int(10)|YES|0|
||expendPoints|已消耗积分|int(10)|YES|0|
||conversionPoints|可用兑换的积分|int(10)|YES||
|
