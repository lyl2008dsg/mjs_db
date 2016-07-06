#loan_pic
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|picId||int(10) unsigned|NO||
|MUL|loanId||int(10) unsigned|NO||
||path|系统内路径|varchar(64)|NO||
||picName|照片名|varchar(50)|NO||
||displayName|照片显示名称|varchar(32)|NO||
||uploadDate|上传时间|datetime|NO||
||picSize|照片大小，单位：字节|int(10) unsigned|NO||
|
