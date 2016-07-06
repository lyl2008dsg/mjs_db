#msg_request
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||varchar(100)|NO||
|PRI|msg_id||varchar(100)|NO||
||description||varchar(255)|YES||
||group_description||varchar(255)|YES||
||group_id||varchar(100)|YES||
||va_id1||varchar(100)|YES||
||va_id2||varchar(100)|YES||
||va_params1||varchar(100)|YES||
||va_params2||varchar(100)|YES||
||value_const||varchar(255)|YES||
||value_example||varchar(255)|YES||
||value_length||int(11)|NO||
||value_scale||int(11)|NO||
|MUL|value_type||varchar(20)|YES||
|
