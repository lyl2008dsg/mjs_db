#collection_staff_task
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|id|int(8)|NO||
||loanId|需要催收的loanId|int(8)|YES||
||staffId|员工id|int(8)|YES||
||status|催收状态00:待催收，01:催收成功，02：催收失败，03：坏账|varchar(2)|YES|00|
||contents|说明|varchar(500)|YES||
|
