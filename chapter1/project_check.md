#project_check
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|checkId|审批id|int(10)|NO||
||pId|项目id|int(10)|NO||
||checkContent|审批意见|varchar(1000)|YES||
||checkStatus|审批状态0-拒绝1-通过|int(4)|YES||
||dIdList|附件id集合，以英文逗号分隔|varchar(50)|YES||
||staffId|员工id|int(10)|NO||
||checkTime|审批时间|datetime|NO||
|
