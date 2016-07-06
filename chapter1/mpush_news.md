#mpush_news
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10)|NO||
||title|标题|varchar(255)|NO||
||text|消息内容|varchar(2000)|NO||
||createtime|建立时间|datetime|NO||
||isPost|是否已经发送 0未发送1已发送|int(1)|NO|0|
||posttime|发送时间|datetime|YES||
||osType|系统的类别0,3:全部 1:Android 2IOS|int(1)|NO|0|
||followUp|后续动作 0打开应用|int(1)|YES|0|
||userType|0全部用户1按条件筛选2特定用户|int(1)|YES|0|
||pushType|推送方式0即时发送1定时发送|int(1)|YES|0|
||offLine|该时间段内cid在线过的用户均可收到通知。(0- 72 小时内的正整数)|int(2)|YES|0|
||beginDate|展示开始时间|datetime|YES||
||endDate|结束时间|datetime|YES||
||users|发送的用户集合已,隔开|text|YES||
|
