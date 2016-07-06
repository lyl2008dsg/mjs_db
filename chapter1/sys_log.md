#sys_log
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|日志id|int(10) unsigned|NO||
||userId|操作用户id|int(10) unsigned|YES||
||logType|日志类型id|varchar(32)|NO||
||userName|用户名称|varchar(19)|YES||
||operModule|操作模块|varchar(32)|YES||
||operType|0=新增,
            1=修改,
            2=删除,
            3=异常
            |smallint(5) unsigned|YES||
||operTime|操作时间|datetime|YES||
||remark|说明|varchar(4000)|YES||
||host|操作IP地址|varchar(20)|YES||
|
