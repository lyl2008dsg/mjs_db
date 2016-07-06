#department
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|部门id|int(10) unsigned|NO||
||departmentType|部门类型|varchar(19)|NO||
||parentDepartmentId|上级部门id|int(10) unsigned|YES||
||isInherit||smallint(5)|YES||
||departmentName|部门名称|varchar(50)|YES||
||departmentCode|部门编码|varchar(50)|YES||
|
