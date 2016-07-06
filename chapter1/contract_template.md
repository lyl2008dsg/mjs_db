#contract_template
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|id|varchar(36)|NO||
||name|模板名称|varchar(100)|YES||
||content|模板内容|text|YES||
||type|模板类型0投资1债权|int(2)|YES||
||isdelete|是否删除0否1是|int(1)|YES|0|
||operatetime|最后一次操作时间|datetime|YES||
||remark|描述|varchar(20)|YES||
||flag|合同状态|varchar(20)|YES||
||code||varchar(1000)|YES||
|
