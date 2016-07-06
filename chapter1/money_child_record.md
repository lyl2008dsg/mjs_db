#money_child_record
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|toUserId|资金汇入者的userid|int(10) unsigned|YES||
||toUserNickname|资金汇入者的昵称|varchar(32)|YES||
|MUL|fromUserId|资金汇出者的userid|int(10) unsigned|YES||
||fromUserNickname|资金汇出者的昵称|varchar(32)|YES||
||amount|交易金额金额|decimal(14,2)|NO||
||accountBalance|此交易完成后的账户余额|decimal(14,2)|NO||
||tradeType|资金来往类型，小于1000的都是汇入，即资金增加；大于1000的都是汇出，即资金减少。详情见CommonDef中TRADE_TYPE_*|smallint(5) unsigned|NO||
|MUL|tradeTime|交易发生时间|datetime|NO||
||tradeChannel|交易渠道|smallint(5) unsigned|YES||
||tradeComment|交易备注|varchar(128)|YES||
||loanId|关联的loanId|int(10) unsigned|YES||
||loanTitle|借款标题|varchar(64)|YES||
||loanPortraitPath|标头像图片的路径|varchar(64)|YES||
||serialNumber|易宝流水号|varchar(80)|YES||
||yeepayStatus|易宝返回的状态|varchar(20)|YES||
||isCheck|平台和易宝对账结果0成功-1失败|varchar(4)|YES|0|
||fundStatus|此记录的资金状态-1 支出 1收入|int(1)|YES|1|
||isShow|是否pc前台显示0不显示1显示|smallint(1)|YES|0|
||finaStatus|财务审核状态01待审核02已拒绝03处理中00已完成|varchar(4)|YES|01|
||arrivalTime|易宝回调时间|datetime|YES||
||serialNumbers|组成该流水的说有易宝流水号|text|YES||
|
