#invited_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|invitedInfoId|邀请记录ID|int(10) unsigned|NO||
|MUL|inviterUserId|发出邀请者的用户ID|int(10) unsigned|NO||
||inviterUserCode|邀请者邀请码|varchar(64)|YES||
||inviteeUserTempId|被邀请者注册tempID|int(10) unsigned|YES||
|UNI|inviteeUserId|被邀请者注册ID|int(10) unsigned|YES||
||inviteeUserChargeTotal|被邀请者的充值总额|decimal(14,2)|YES|0.00|
||inviteeUserInvestTotal|被邀请者的投资总额|decimal(14,2)|YES|0.00|
||inviteeRegDate|被邀请者的注册时间|datetime|YES||
||inviteeActiveDate|被邀请者的激活时间|datetime|YES||
||inviteeLastChargeDate|被邀请者的最后充值时间|datetime|YES||
||inviteeLastInvestDate|被邀请者的最后投资时间|datetime|YES||
||inviteeRegIP|被邀请者注册IP地址|int(10)|YES||
||inviteeActiveIP|被邀请者激活IP地址|int(10)|YES||
||rewardPaidStatus|奖品清算标志位，参考CommonDef中CASH_BACK_STATUS_*|int(10) unsigned|YES|700|
||scoreBlotterId||int(10)|YES||
||inviterUserRewardTotal|奖励金额|decimal(14,2)|YES|0.00|
|
