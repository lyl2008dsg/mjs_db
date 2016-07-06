#borrower_contact
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|borrowerId|借款者ID|int(10) unsigned|NO||
||name|联系人中文姓名|varchar(20)|YES||
||relationship|关系|smallint(6)|YES||
||mobile|联系人手机|varchar(16)|YES||
||telephone|联系人固定电话|varchar(16)|YES||
||contactProvice|联系人地址-省份|varchar(12)|YES||
||contactCity|联系人地址-市|varchar(12)|YES||
||contactCountry|联系人地址-县|varchar(12)|YES||
||contactAddress|联系人地址-地址|varchar(64)|YES||
||contactWorkProvice|联系人工作地址-省份|varchar(12)|YES||
||contactWorkCity|联系人工作地址-市|varchar(12)|YES||
||contactWorkCountry|联系人工作地址-县|varchar(12)|YES||
||contactWorkAddress|联系人工作地址-地址|varchar(64)|YES||
||remark|备注|varchar(512)|YES||
||isDisplay|是否显示|tinyint(1)|NO|1|
||isAddByFront|是否是前台添加|tinyint(1)|NO|1|
|MUL|loanId|标ID|int(10)|YES||
|
