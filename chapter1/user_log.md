#user_log
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|主键UUID|varchar(32)|NO||
||log_time|当前时间|datetime|YES||
||module_url|当前用户所处的URL|操作模块/页面|varchar(255)|YES||
||user_id|当前用户或匿名用户|varchar(32)|YES||
||operation|操作类型/编码|varchar(32)|YES||
||target_id|æ“ä½œå¯¹è±¡ID|varchar(255)|YES||
||target_type|操作对象类型, 产品/标的/用户|varchar(32)|YES||
||detail|操作内容,详细描述|text|YES||
||ip|访问IP|varchar(32)|YES||
||session_id||varchar(36)|YES||
||remainTime|é¡µé¢åœç•™æ—¶é—´|int(10)|YES|0|
|
