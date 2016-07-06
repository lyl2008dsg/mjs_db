#loan_comment
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|commentId||int(10) unsigned|NO||
|MUL|commentTime||datetime|NO||
||content||varchar(500)|NO||
||commentIdreplyTo|è¢«å›žå¤çš„ç•™è¨€çš„commentIdï¼Œç”¨ä»¥å»ºç«‹å›žå¤å…³ç³»|int(10) unsigned|YES||
|MUL|byUserId|ç•™è¨€ç”¨æˆ·id|int(10) unsigned|NO||
||byUserRoles|è§’è‰²|smallint(5) unsigned|YES||
||byUserNickName|ç•™è¨€ç”¨æˆ·æ˜µç§°|varchar(32)|NO||
|MUL|toLoanId|å›žå¤çš„loançš„id|int(10) unsigned|NO||
||userPicId|ç”¨æˆ·å¤´åƒid|int(10) unsigned|YES||
||userPicPath|ç”¨æˆ·å¤´åƒè·¯å¾„|varchar(64)|YES||
||isDisplay|æ˜¯å¦æ˜¾ç¤º|tinyint(1)|NO|1|
||status|å®¡æ ¸çŠ¶æ€|int(2)|YES|0|
|
