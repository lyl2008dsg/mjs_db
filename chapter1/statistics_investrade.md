#statistics_investrade
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|主键UUID|varchar(32)|NO||
||sdate|统计日期|date|YES||
||veidoo_id|维度值|varchar(32)|YES||
||invest_people|投资人数|int(11)|YES||
||invest_count|投资笔数|int(11)|YES||
||invest_amount|投资总金额|decimal(14,2)|YES||
||invest_per_amount|平均每笔成交金额|decimal(14,2)|YES||
|
