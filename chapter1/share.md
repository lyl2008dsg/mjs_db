#share
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||varchar(36)|NO||
||title|分享标题|varchar(200)|YES||
||createdate|创建时间|datetime|YES||
||link|分享链接|varchar(255)|YES||
||content|分享内容|varchar(10000)|YES||
||type|1为邀请好友，2为标的分享|int(11)|YES||
||pictureName|图片|varchar(200)|YES||
|
