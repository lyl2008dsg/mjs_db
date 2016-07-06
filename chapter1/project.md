#project
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|projectId|项目编号|int(10)|NO||
||projectNum|项目编号|varchar(50)|YES||
||projectName|项目名称|varchar(255)|YES||
||projectEnterprise|融资企业|varchar(50)|YES||
||projectType|项目类型0-直融类1-通道类|int(2)|NO|0|
||projectInterestRate|融资利率|decimal(4,2)|YES||
||projectAmount|融资金额|decimal(14,2)|NO||
||projectTermCount|融款期限|smallint(5)|NO||
||projectTermUnit|期限单位1-天2-周3-月4-年|smallint(5)|NO||
||projectAssusre|担保方|varchar(50)|YES||
||projectUse|融资用途|text|YES||
||projectFrom|来源机构|varchar(50)|YES||
||projectIntroduce|项目介绍|text|YES||
||projectInnerStatus|内部复审状态：0-复审未提交1-复审已提交2-复审已拒绝3-复审已通过|int(4)|NO|0|
||projectOutStatus|审批状态：0-未发起审批1-审核中2-审批拒绝3-审批通过|int(4)|YES||
||projectSumbitTime|提交时间|datetime|YES||
||projectSaveTime|保存时间|datetime|YES||
||projectAgreementStatuts|协议附加状态0-未附加1-已附加|int(4)|NO|0|
||projectContractId|协议模板id|varchar(36)|YES||
||projectAgreementNo|协议编号|varchar(50)|YES||
||projectStaffListId|归属员工列表|varchar(255)|YES||
||projectCreateStaffId|创建人id|int(10)|NO||
||projectCreateStaffName|创建人名称|varchar(50)|YES||
||projectNowCheckStaffId|当前审批员工id|int(10)|YES||
||remark|备注|varchar(50)|YES||
|
