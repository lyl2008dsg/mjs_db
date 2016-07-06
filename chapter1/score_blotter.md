#score_blotter
* 积分流水表
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|userId|用户userid|int(10) unsigned|NO|0|
||userName|用户名|varchar(64)|NO||
||createTime|流水时间|datetime|NO||
|MUL|bizId|加积分类型id|int(10) unsigned|YES||
||bizName|加积分类型|varchar(64)|YES||
|MUL|goodsId|兑换积分类型id|int(10) unsigned|YES||
||goodsName|兑换积分类型名|varchar(64)|YES||
||price|兑换物品单价|int(11)|YES||
||points|操作积分数|int(10)|NO|0|
||status|状态，0加积分，1兑换积分(冻结)，2兑换积分(成功)，3兑换积分(失败)|int(11)|NO|0|
|
