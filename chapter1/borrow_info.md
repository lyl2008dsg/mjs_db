#borrow_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
||isBusiness|是否非普业务 1-非普，0-普通|varchar(2)|YES||
||business_type|业务品种:详情参考Conts.BUSINESS_TYPE_*|varchar(10)|YES|1|
||replyNum|批复文号|varchar(100)|YES||
||organization_code|组织机构代码证|varchar(100)|YES||
||enterprise_name|企业名称\借款人姓名|varchar(100)|YES||
||ratings_result|评级结果|varchar(500)|YES||
||isInBlacklist|是否黑名单客户|varchar(10)|YES||
||amount_begin_date|额度起始日|datetime|YES||
||amount_end_date|额度到期日|datetime|YES||
||limit_type|额度种类|varchar(50)|YES||
||credit_currency|对应授信金额币别|varchar(10)|YES||
||credit_contract_no|对应授信合同号|varchar(50)|YES||
||total_contract_amount|合同总金额|decimal(14,2)|YES||
||credit_balance|授信余额    |decimal(14,2)|YES||
||available_balance|可用余额|decimal(14,2)|YES||
||isReplyAvailable|批复是否有效|varchar(10)|YES||
||public_account|对公结算账号|varchar(50)|YES||
||insterst_type|付息方式 Conts.INTEREST_TYPE_*|int(10)|NO|1|
||borrow_purpose|借款用途|varchar(500)|YES||
||pay_type|支付方式:Const.PAY_TYPE_*|int(10)|YES||
||receiver_bank|收款人开户行|varchar(50)|YES||
||receiver_name|收款人名称|varchar(30)|YES||
||receiver_account|收款人账号|varchar(50)|YES||
||collateral_name|担保品名称|int(200)|YES||
||collateral_code|担保品编号     |varchar(50)|YES||
||business_account|业务账号     |varchar(50)|YES||
||collateral_security_amount|担保金额|decimal(10,2)|YES||
||householder_name||varchar(50)|YES||
||collateral_status|担保品状态|varchar(20)|YES||
||collateral_due_date|担保品到期日|datetime|YES||
||start_interest_time|项目起息日|datetime|YES||
||end_time|项目到期日|datetime|YES||
||longest_deadline|项目最长期限|int(11)|YES||
||borrow_rate|借款利率|decimal(14,2)|YES||
||invest_rate|投资人利率|decimal(14,2)|YES||
||charge_rate|费率|decimal(14,2)|YES||
||borrow_account|借款金额|decimal(14,0)|YES||
||mark||text|YES||
||createTime|导入日期|datetime|YES||
||groupFlag|集团标志|varchar(100)|YES||
||replyTime|批复日期|datetime|YES||
||industry|行业|varchar(100)|YES||
||replyMaturityTime|批复到期日|datetime|YES||
||business_scope|经营范围|varchar(200)|YES||
||risk_category_result|风险分类结果|varchar(500)|YES||
||run_age_limit|经营年限|int(11) unsigned|YES||
||enterprise_scale|规模|varchar(50)|YES||
||staff_account|员工人数|int(11)|YES||
||credit_line|授信额度|decimal(14,2)|YES||
||total_credit_line|总授信额度|decimal(14,2) unsigned|YES||
||total_credit_available_line|总授信可用额度|decimal(14,2)|YES||
||customer_manager_idcard|贷信经办人身份证号码|varchar(20)|YES||
||customer_manager_type|信贷经办人证件类型|varchar(30)|YES||
||customer_manager_name|客户经理姓名|varchar(10)|YES||
||project_application_agency|项目申请机构|varchar(100)|YES||
||staffId||int(10)|NO||
||status|重要:0-保存状态，1-提交状态,2-审核通过，3-审核失败|int(6)|YES||
||loanCode|项目编号,CD+8位日期+3位数字|varchar(14)|YES||
||staff_parent_departments|业务经理所有的上级部门，以","分割|varchar(60)|YES||
||in_storage_time|入库时间|datetime|YES||
||customer_mgr_name|借款信息录入客户经理姓名，主要用于查询|varchar(30)|YES||
||branch_mgr_name|分行审核人员,主要用于查询|varchar(30)|YES||
||org_name|机构名称|varchar(150)|YES||
|
