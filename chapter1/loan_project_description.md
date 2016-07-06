#loan_project_description
* 标的项目说明
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|唯一标识|int(11)|NO||
||loanId|标id|int(11)|NO||
||type|A("公司介绍"), C("风险揭示"), D("免责声明"), E("交易说明书")|varchar(32)|NO||
||typeDesc|A("公司介绍"), C("风险揭示"), D("免责声明"), E("交易说明书")|varchar(256)|NO||
||content||text|YES||
||createTime||date|YES||
||updateTime||date|YES||
||updateUserid|修改人的唯一标识|int(11)|YES||
||updateUserName|修改人的姓名|varchar(64)|YES||
|
