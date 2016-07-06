#project_task_num
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|id|int(10)|NO||
||tId|任务id，和project_task里taskId相关连|int(10)|NO||
||pId|项目id|int(10)|NO||
||stepNum|所在步骤|int(10)|YES||
||stepName|步骤名称|varchar(50)|YES||
||status|审核状态0-审核中1-审核通过2-拒绝3-为开始|int(4)|YES|0|
||remark|备注|varchar(50)|YES||
|
