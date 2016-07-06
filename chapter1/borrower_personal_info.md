#borrower_personal_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|userPersonalInfoId||int(10) unsigned|NO||
|MUL|userId|用户id，和user_main.userId关联|int(10) unsigned|NO||
|MUL|loanId|标id，让个人信息跟着标走|int(10) unsigned|YES||
||totalCreditLimit|授信额度，即最多能借多少钱|decimal(14,2)|NO|0.00|
||avaliableCreditLimit|剩余授信额度，即减去已经发的标，目前还能发多少额度的标|decimal(14,2)|NO|0.00|
||creditPoint|信用分数|smallint(5) unsigned|NO|0|
||formerName|曾用名|varchar(20)|YES||
||gender|性别，女：false；男：true com.zkbc.core.consts.user.GenderType|tinyint(1)|YES||
||mobile|手机号码（此时不确定是否绑定）|varchar(11)|YES||
||telephone|固定电话|varchar(18)|YES||
||birth|生日|date|YES||
||homeTownProvince|籍贯-省份|varchar(12)|YES||
||homeTownCity|籍贯-城市|varchar(12)|YES||
||homeTownCounty|籍贯-县|varchar(12)|YES||
||homeTownAddr|籍贯-地址|varchar(64)|YES||
||residenceProvince|居住地-省份|varchar(12)|YES||
||residenceCity|居住地-城市|varchar(12)|YES||
||residenceCounty|居住地-县|varchar(12)|YES||
||residenceAddr|居住地-地址|varchar(64)|YES||
||residencePostCode|居住地-邮编|varchar(6)|YES||
||qq|QQ|varchar(16)|YES||
||topEducation|最高学历|smallint(5) unsigned|YES||
||topEduStartYear|最高学历入学年份|smallint(5) unsigned|YES||
||topEduSchool|毕业院校|varchar(32)|YES||
||hasMarried|是否结婚|tinyint(1)|YES||
||hasChild|是否有孩子|tinyint(1)|YES||
|
