#activity
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(11)|NO||
||title|标题,支持HTML,例如：新手特权，注册就送99！(1元玩转理财不是梦！)|text|NO||
||start_date|活动开始日期|datetime|NO||
||end_date|活动结束日期|datetime|NO||
||create_date|活动创建日期|datetime|YES||
||create_userid|创建人staffid|int(10)|YES||
||link|活动链接|varchar(255)|YES||
||banner_path|banner文件路径|varchar(255)|YES||
||banner_id|文件对应的ID|varchar(64)|YES||
||is_push|是否推送 0不推送 1推送，全部退sing|tinyint(1)|YES||
||users_id|用户的ID，例如：10001,10002,1003|text|YES||
||push_way|推送方式,#1#,站内信 #2#,邮件 #3#,短信 示例：#1#2###3#|varchar(255)|YES||
||push_date|推送日期|datetime|YES||
||is_pushed|是否已经推送|tinyint(1)|YES|0|
||msgs_id|消息队列的ID集合|text|YES||
|
