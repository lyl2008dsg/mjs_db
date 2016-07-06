#score_goods
* 积分兑换物品表
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|Id||int(10)|NO||
||goodsName|兑换物品名|varchar(64)|NO||
||points|消耗积分|int(10)|NO|0|
||type|兑换类型，0虚拟，1实物|int(11)|NO|0|
||remark|备注|varchar(255)|YES||
||pictureName|前台显示图片|varchar(128)|YES||
||pictureId|兑换物品Id名称|varchar(64)|YES||
||price|货物价值|int(10)|YES|0|
||createTime|创建时间|datetime|YES||
||isDisplay|是否在前台显示：状态0：不显示；状态1：显示；默认为不显示|int(10)|YES|0|
|
