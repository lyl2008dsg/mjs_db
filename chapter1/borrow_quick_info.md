#borrow_quick_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|抵押图片编号|int(10) unsigned|NO||
||loanId|标ID|int(10) unsigned|YES||
||userId|用户ID|int(10) unsigned|NO||
||purposes|借款用途|varchar(100)|NO||
||amount|借款金额|decimal(14,2)|NO||
||limit|借款期限|int(10)|NO||
||phoneNo|联系手机|varchar(20)|NO||
||describe|借款描述|varchar(500)|NO||
||applyTime|申请时间|datetime|NO||
||status|申请状态|int(10)|NO||
||reason||varchar(200)|YES||
||auditTime||datetime|YES||
||auditPerson||int(10)|YES||
|
