#biz_loaner
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10)|NO||
||user_name|用户名|varchar(24)|NO||
||biz_name|企业全称|varchar(24)|YES||
||biz_brifename|企业简称|varchar(24)|YES||
||create_time|创建时间|datetime|YES||
||recommender|推荐人|varchar(24)|YES||
||charge|负责人,存的是user_main 表中的userId值|int(10)|NO||
||type|公司类型|varchar(24)|YES||
||classification|类别|varchar(24)|YES||
||organization_code|组织机构代码|varchar(20)|YES||
||instructions||varchar(1024)|YES||
||tax_code|税务登记号|varchar(20)|YES||
||website|企业网址|varchar(24)|YES||
||adress|企业地址|varchar(24)|NO||
||scope|经营范围|varchar(24)|YES||
||descripetion|企业描述|varchar(60)|YES||
||linkman|联系人|varchar(24)|YES||
||phone|联系电话|varchar(24)|YES||
||e_mail|联系邮箱|varchar(24)|YES||
||capital|注册资本|varchar(24)|YES||
||registered_address|注册地址|varchar(24)|YES||
||corporater|企业法人|varchar(24)|YES||
||business_state|经营状况|varchar(500)|YES||
||bankLicense|银行开户许可证|varchar(255)|YES||
|
