#project_task_staff
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|numId|步骤成员id|int(10)|NO||
||pid|项目id|int(10)|NO|0|
||tid|任务id|int(10)|NO||
||ptnId|任务所属步骤id|int(10)|NO||
||partmentId|员工所属部门id|int(10)|NO||
||staffId|员工id|int(10)|NO||
||stepNum|所属步骤|int(10)|NO||
||staffNum|该步骤下第几个员工|int(10)|NO||
||staffRealName|审核人员真实姓名|varchar(50)|YES||
||staffRole|审核人员角色|varchar(50)|YES||
||status|审批状态：0-审核中1-已拒绝2-已通过3-为开始|int(4)|YES|0|
|
