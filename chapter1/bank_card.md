#bank_card
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id||int(10) unsigned|NO||
|MUL|userId|é“¶è¡Œå¡æŒæœ‰è€…ç”¨æˆ·id|int(10) unsigned|NO||
||userRealName|æŒå¡äººçš„çœŸå®žå§“å|varchar(25)|YES||
||cardNo|é“¶è¡Œå¡å·|varchar(35)|NO||
||bankCode||varchar(4)|YES||
||accountBankName|å¼€æˆ·è¡Œåç§°|varchar(64)|YES||
||accountBankId|å¼€æˆ·è¡Œè¡Œå·ï¼Œå¦‚001121004527|varchar(12)|YES||
||isBinded|æ˜¯å¦å·²ç»‘å®š|bit(1)|NO||
||isSendUnbind|是否发送解绑信息,0没有发送过请求，1已经发送过请求|int(1)|YES|0|
||bkdate||datetime|YES||
|
