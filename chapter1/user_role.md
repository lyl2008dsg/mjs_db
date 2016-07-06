#user_role
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|角色id|int(10) unsigned|NO||
||departmentId|待扩展角色归属|int(10) unsigned|YES||
||roleName|角色名称id|varchar(50)|YES||
||roleType|
            0=业务类型,
            1=管理类型
            |smallint(5) unsigned|YES||
||remark|备注|varchar(1000)|YES||
|
