#borrower_work_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|userWorkInfoId||int(10) unsigned|NO||
|MUL|userId||int(10) unsigned|NO||
|MUL|loanId|标id|int(10) unsigned|YES||
||officeName|办公名称|varchar(64)|YES||
||officeProvice|办公地址-省份|varchar(12)|YES||
||officeCity|办公地址-市|varchar(12)|YES||
||officeCounty|办公地址-县|varchar(12)|YES||
||officeAddress|办公地址-地址|varchar(64)|YES||
||officeType|单位性质。1：机关事业单位；2：国营；3：民营；4：三资企业；5：其他|smallint(5) unsigned|YES||
||officeJoinDate|进入该单位时间|datetime|YES||
||department|所在部门|varchar(64)|YES||
||position|担任职务。1：管理、技术、行政岗位；2：销售岗位；3：其他基层服务岗位|smallint(5) unsigned|YES||
||officePhone|工作电话|varchar(16)|YES||
||officeSize|公司规模|varchar(16)|YES||
||industry|所属行业。1：政府机构、军事机关；2，教育科研、医院、公共事业、金融业；3：建筑业、传统制造业、高新技术制造业；4：其他|smallint(5) unsigned|YES||
||officeLaunchedTime|创办时间|varchar(16)|YES||
||registeredCapital|单位注册及实收资本|decimal(16,2)|YES||
||isLegalRepresentative|借款人是否是法人|tinyint(1)|YES||
||isStockholder|借款人是否是股东|tinyint(1)|YES||
||shareholdingRatio|持股比例:1.50%及以上;2.40%-<50%;3.30%-<40%;4.20%-<30%|smallint(5) unsigned|YES||
||businessLife|借款人本行业从业年限:1.10年（含）以上;2.6-9年;3.3-5年;4.2年以下|smallint(5) unsigned|YES||
||housingState|公司房产状况:1.“贷款购置房屋”，应该填写“房贷”、“面积”；2.“自购房屋，无房贷”；3.“租房”，应该填写“房租”|smallint(5) unsigned|YES||
||monthlyHouseLoan|房贷|decimal(16,2)|YES||
||housingArea|面积，单位：平方米|int(10) unsigned|YES||
||monthlyHouseRent|房租|decimal(16,2)|YES||
||registrationNumber|工商登记号|varchar(15)|YES||
||taxCode|税务编号|varchar(15)|YES||
||officeAnnualProfits|公司年利润|varchar(16)|YES||
||monthlyTurnover|月均营业额销售额|decimal(16,2)|YES||
||monthlyFixedCost|月固定运营成本|varchar(16)|YES||
||grossMarginRate|毛利润率|decimal(4,2)|YES||
||updownStreamCustomers|上下游客户|varchar(64)|YES||
||settlementMode|上下游客户结算方式|varchar(16)|YES||
||employeesNumber|员工人数|varchar(6)|YES||
||creditDimensions|应收账款规模|varchar(16)|YES||
||creditAge|应收账款账龄 ，单位：天|varchar(6)|YES||
||creditRecoveryCycle|应收账款的回收周期 ，单位：天|varchar(6)|YES||
||monthlyIncome|可认定的月收入额|varchar(16)|YES||
|
