#trade
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|serial_number|流水号|varchar(80)|NO||
||user_ID|用户标识|int(50)|YES||
||message_ID|报文标识|varchar(50)|YES||
||request_message|请求报文|text|YES||
||response_message|响应报文|text|YES||
||request_trading_account|请求交易账户|varchar(60)|YES||
||request_trading_amount|请求交易金额|decimal(50,2)|YES||
||response_trading_account|响应交易账号|varchar(60)|YES||
||response_trading_amount|响应交易金额|decimal(50,2)|YES||
||trade_status|交易状态|varchar(10)|YES||
||trade_date|交易时间|datetime|YES||
||loanid|标信息|int(30)|YES||
||loan_phase_id|还款（借款标id）|int(50)|YES||
||loan_investor_id|债券转让（投标id）|int(50)|YES||
||request_id|请求id（用于取现）|int(50)|YES||
||trxId|第三方响应流水号|varchar(100)|YES||
||freeze_trxId|冻结资金流水号（支付生成）|varchar(100)|YES||
||freeze_ordId|冻结资金流水|varchar(100)|YES||
||unfreeze_ordId|解冻订单号（客户请求）|varchar(100)|YES||
||debt_ord_id|债权转让成功订单号（用在还款中）|varchar(100)|YES||
||debt_ord_date|债权转让成功时间（用在还款中）|datetime|YES||
||version||int(11)|YES|0|
|
