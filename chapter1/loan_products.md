#loan_products
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|id|int(10)|NO||
||productstype|产品类型|varchar(20)|YES||
||rate|基准利率|decimal(15,2)|YES||
||beginratescope|利率范围开始|decimal(15,2)|YES||
||endratescope|利率范围结束|decimal(15,2)|YES||
||termtype|期限类型|int(5)|YES||
||begintermscope|期限范围开始|varchar(10)|YES||
||endtermscope|期限范围结束|varchar(10)|YES||
||platformfee|平台手续费|decimal(15,2)|YES||
||riskmargin|风险保证金|decimal(15,2)|YES||
||repaytype|还款方式|varchar(10)|YES||
||features|产品特点|varchar(4000)|YES||
||conditions|申请条件|varchar(4000)|YES||
||materials|必要申请资料|varchar(4000)|YES||
||status|是否前台显示|int(2)|NO|0|
||loanmoneymax||decimal(15,2)|YES||
||loanmoneymin||decimal(15,2)|YES||
||type|标类型:1-个人借款产品；2-企业借款产品|int(2)|NO||
||isexperience||int(2)|NO|0|
||procedureway|付费方式|varchar(10)|YES||
||projectType|项目类型0-直融类1-通道类|int(4)|YES||
|
