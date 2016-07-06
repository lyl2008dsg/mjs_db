#overdue_collection
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|loanId|关联的标id|int(10) unsigned|YES||
|MUL|loanPhaseId|关联的还款分期id|int(10) unsigned|YES||
||collectionStaffId|催收的员工id|int(10) unsigned|YES||
||collectionStaffName|催收的员工姓名|varchar(16)|NO||
||collectionTime|催收时间|datetime|YES||
||collectionType|催收方式|smallint(5) unsigned|YES||
||collectionDetail|催收详情，结果|varchar(256)|YES||
||collectionRepayment|催收还款|decimal(14,2)|YES||
|
