#project_doc
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|docId|附件id|int(10)|NO||
||pId|项目id|int(10)|NO||
||docType|附件类型，1-项目附件2-审核附件3-项目协议附件|int(2)|YES||
||docName|附件名称|varchar(50)|YES||
||docPath|附件路径|varchar(255)|YES||
||docSize|附件大小|int(10)|YES||
||uploadTime|上传时间|datetime|YES||
|
