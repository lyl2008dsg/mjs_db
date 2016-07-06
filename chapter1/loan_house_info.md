#loan_house_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|房屋编号|int(10) unsigned|NO||
||loanId|标ID|int(10) unsigned|NO||
||privinceNo|省ID|int(10) unsigned|NO||
||cityNo|市ID|int(10) unsigned|NO||
||countyNo|县ID|int(10) unsigned|NO||
||plot|小区名称|varchar(100)|NO||
||address|房屋地址|varchar(100)|NO||
||area|建筑面积|decimal(14,2)|NO||
||completedYear|竣工年份|int(4)|NO||
||toward|朝向|varchar(100)|NO||
||layerNumber|层数|int(4)|NO||
||mortgage|抵押权顺位 1=清房/2=按揭/3=抵押/4=借款/5=其他|varchar(1)|NO||
||amount|评估金额|decimal(14,2)|NO||
||borrowAmount|贷（借）金额|decimal(14,2)|NO||
||borrowYear|贷（借）年限|int(4)|NO||
||repayAmount|已还金额|decimal(14,2)|NO||
||remainAmount|剩余贷款|decimal(14,2)|NO||
||repayDegree|落实还款程度|varchar(10)|NO||
||dockPerson|对接人|varchar(20)|NO||
|
