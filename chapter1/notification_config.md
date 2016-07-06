#notification_config
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|userId|用户ID|int(10) unsigned|NO||
||investorInvest|投资者-已投标|smallint(5) unsigned|NO|1|
||investorRepay|投资者-已投的标回款|smallint(5) unsigned|NO|7|
||investorLoanDead|投资者-已投的标流标|smallint(5) unsigned|NO|1|
||investorLoanReleased|投资者-已投的标放款|smallint(5) unsigned|NO|1|
||investorNewProduct|投资者-平台的新产品|smallint(5) unsigned|NO|1|
||investorCommentReplied|投资者-留言被回复|smallint(5) unsigned|NO|1|
||borrowerLoanReleased|借款者-满标放款|smallint(5) unsigned|NO|1|
||borrowerLoanRejected|借款者-审核未通过|smallint(5) unsigned|NO|1|
||borrowerLoanDead|借款者-流标|smallint(5) unsigned|NO|1|
||borrowerPlatformNotice|借款者-平台通知|smallint(5) unsigned|NO|1|
||borrowerRepayReminder|借款者-提前3天还款提醒|smallint(5) unsigned|NO|7|
||borrowerOverDueNotice|借款者-逾期通知|smallint(5) unsigned|NO|7|
||messageSetup|新的消息设置类型|varchar(300)|NO||
|
