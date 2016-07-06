#loan_project
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|projectId|项目编号|int(10)|NO||
||projectNum|项目编号|varchar(50)|YES||
||projectName|项目名称|varchar(255)|YES||
||projectEnterprise|融资企业|varchar(50)|YES||
||projectType|项目类型0-直融类1-通道类|int(2)|NO|0|
||projectInterestRate|融资利率|decimal(4,2)|YES||
||projectAmount|融资金额|decimal(14,2)|NO|0.00|
||projectTermCount|融款期限|smallint(5)|NO||
||projectTermUnit|期限单位1-天2-周3-月4-年|smallint(5)|NO||
||projectAssusre|担保方|varchar(50)|YES||
||projectUse|融资用途|text|YES||
||projectFrom|来源机构|varchar(50)|YES||
||projectIntroduce|项目介绍|text|YES||
||projectRepayFrom|还款来源|text|YES||
||projectRisk|风控保障|text|YES||
||projectSaveTime|保存时间|datetime|YES||
||remark|备注|varchar(50)|YES||
||loanId|标id|int(10)|NO||
||filePath|附件路径|varchar(250)|YES||
||fileName|附件名称|varchar(50)|YES||
|
