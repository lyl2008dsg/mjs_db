#borrower_financial_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|userFinancialInfoId||int(10) unsigned|NO||
|MUL|userId||int(10) unsigned|NO||
|MUL|loanId|标id|int(10) unsigned|YES||
||monthlyIncome|个人月收入|decimal(16,2)|YES||
||payDay|发薪日|varchar(16)|YES||
||payType|发薪方式|smallint(5) unsigned|YES||
||housingType|住房种类，1：无房；2，有房无贷款；3，有房有贷款|smallint(5) unsigned|YES||
||housingYear|购房年份|smallint(5) unsigned|YES||
||housingArea|房产面积，单位：平方米|int(10) unsigned|YES||
||monthlyHouseLoan|月供/月租金|decimal(16,2)|YES||
||hasCar|名下有无汽车|tinyint(1)|YES||
||carYear|购车年份|smallint(5) unsigned|YES||
||carBrand|汽车品牌|varchar(16)|YES||
||monthlyCarLoan|汽车月供|decimal(16,2)|YES||
||carValue|汽车价值，1，30万以上且有贷；2，30万以下且有贷；3，30万以上且无贷款；4,30万以下且无贷款|smallint(5) unsigned|YES||
||hasBond|名下有无证券 |tinyint(1)|YES||
||bondValue|证券价值|decimal(16,2)|YES||
||monthlyDisposableIncome|月可支配收入|int(10) unsigned|YES||
||disposableIncomeRatio|支配收入覆盖比|smallint(5) unsigned|YES||
|
