#loan_audit_record
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|auditorId|审批者的id 或分配者的staffid|int(10) unsigned|NO||
||auditorName|审批者姓名|varchar(50)|NO||
||actionType|动作类型：包括审批，分配审批任务等|smallint(5) unsigned|NO||
||loanId|被审批的loan的id|int(10) unsigned|NO||
||auditResult|审批结果，请参考com.zkbc.core.consts.LoanDef|smallint(5) unsigned|NO||
||auditComment|审批意见|varchar(512)|NO||
||actionTime|提交动作（审批，退回，包括分配任务等动作发生的时间）|datetime|NO||
|
