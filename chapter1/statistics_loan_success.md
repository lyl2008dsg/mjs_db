#statistics_loan_success
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|主键UUID|varchar(32)|NO||
||sdate|统计日期|date|YES||
||veidoo_id|维度值|varchar(32)|YES||
||personAmount|成交人数|varchar(11)|YES||
||amount|成交笔数|int(11)|YES||
||money|总金额|decimal(14,2)|YES||
||per_money|平均每笔成交金额|decimal(14,2)|YES||
|
