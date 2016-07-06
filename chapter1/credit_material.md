#credit_material
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|userId|上传认证材料的用户id|int(10) unsigned|NO||
||loanId|此认证材料上传时，其关联的标id。此值可能为空，因为用户可能在没有任何借款申请的情况下提交新的认证材料|int(10) unsigned|YES||
||materialType|认证材料的类型，见com.zkbc.core.consts.LoanDef.CREDIT_MATERIAL_TYPE|varchar(4)|NO||
||state|认证材料的状态，见com.zkbc.core.consts.LoanDef.CREDIT_MATERIAL_STATE|smallint(5) unsigned|NO|0|
||uploadTime|上传时间|datetime|NO||
||point|此材料带来的认证分数|smallint(5) unsigned|YES|0|
||filePath|文件路径|varchar(64)|NO||
||fileName|文件名|varchar(64)|NO||
||fileSize|照片大小，单位：字节|int(10) unsigned|NO||
||isMasked|此材料是否有加马赛克的版本，默认：无|tinyint(1)|NO|0|
||maskedFilePath|文件路径-打马赛克的|varchar(64)|YES||
||maskedFileName|文件名-打马赛克的|varchar(64)|YES||
||maskedFileSize|照片（打马赛克的）大小，单位：字节|int(10) unsigned|YES||
||auditStaffId|审核此材料的员工id|int(10) unsigned|YES||
||passedTime|认证通过的时间|datetime|YES||
||isDeleted|是否被删除，默认“否”。此表中的记录只能逻辑删除|tinyint(1)|NO|0|
|
