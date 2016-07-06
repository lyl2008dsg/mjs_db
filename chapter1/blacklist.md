#blacklist
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
||userId||int(10) unsigned|YES||
||source|黑名单来源|varchar(32)|YES||
||email|邮件，要求唯一|varchar(32)|YES||
||nickName|用户昵称，不要求唯一|varchar(32)|YES||
||mobile|手机号码，不要求唯一|varchar(11)|YES||
||realName|真实姓名|varchar(16)|NO||
||idCardNo|身份证号|varchar(18)|NO||
||address|居住地址|varchar(256)|YES||
||office|公司名称|varchar(64)|YES||
||officeAddress|公司地址|varchar(512)|YES||
||overdueAmounts|逾期未还款笔数|int(10) unsigned|YES||
||spotAmounts|网站垫付款笔数|int(10) unsigned|YES||
||maxOverdueDays|最长逾期天数|int(10) unsigned|YES||
||totalArrears|欠款总额|decimal(12,2)|YES||
||updateTime|更新时间|datetime|YES||
||path|系统内路径|varchar(64)|YES||
||picName|照片文件名|varchar(50)|YES||
||displayName|照片显示名称|varchar(32)|YES||
|
