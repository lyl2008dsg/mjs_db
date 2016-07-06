#app_version
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|version_id|版本Id|int(10)|NO||
||version_name|版本名称|varchar(255)|YES||
||version_number|版本号|varchar(255)|YES||
||upgrade_properties|版本属性|varchar(255)|YES||
||dowload_add|版本地址|varchar(255)|YES||
||release_time|发布时间|datetime|YES||
||version_desc|版本描述|varchar(255)|YES||
||version_type|版本类型:1表示ios类型，2表示Android类型|smallint(5)|YES||
||md5||varchar(64)|YES||
|
