#image_text
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|pictureId|图文Id|char(50)|NO||
||imgUrl|封面路径|varchar(100)|YES||
||describetion|描述|varchar(150)|YES||
||picConn|链接地址|varchar(512)|YES||
||textVal|正文|longtext|YES||
||picTitle|图文标题|varchar(100)|YES||
||showImg|是否在详情页显示封面（0.否；1.是）|int(2)|YES|0|
||author|作者|varchar(100)|YES||
||bustRela|请求类型(1.关注；2.关键字；3.消息自动回复；4.自定义回复；5.推送消息)|varchar(50)|YES||
||types|消息类型（1.文本；2.图文）|int(2)|YES||
||template|模版Id|varchar(200)|YES||
||createTime|创建时间|datetime|NO||
||createUser|创建用户|varchar(50)|YES||
||updateTime|更新时间|datetime|YES||
||updateUser|更新用户|varchar(50)|YES||
||status|删除状态（0.已删除；1未删除）|int(2)|YES||
||mediaId|媒体文件上传后，获取时的唯一标识|varchar(100)|YES||
||parentId|父id|varchar(40)|YES||
||keyword|关键字|varchar(50)|YES||
||picType|图片类型(1.单图文，2.多图文)|int(1)|YES||
||sortId|记录序号|int(2)|YES||
|
