#statistics_register
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|主键UUID|varchar(32)|NO||
||sdate|统计日期|date|YES||
||veidoo_id|维度值|varchar(32)|YES||
||amount|注册量|int(11)|YES||
||borrow_amount|当日注册借款数量|int(11)|YES||
||invest_amount|当日注册投资数量|int(11)|YES||
|
