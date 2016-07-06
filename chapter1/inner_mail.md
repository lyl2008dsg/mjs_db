#inner_mail
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
||content|内容|varchar(1000)|NO||
||context|引用的内容|varchar(1000)|YES||
|MUL|receiver|收件人|int(10) unsigned|NO||
|MUL|sender|发件人|int(10) unsigned|NO||
||isread|是否已读，默认否|tinyint(1)|NO|0|
||isOutstanding|是否红旗，默认否|tinyint(1)|NO|0|
||messageType|站内信类型|smallint(5) unsigned|NO||
||sendtime||datetime|NO||
|
