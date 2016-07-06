#user_login_failure
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|userId|用户id|int(10) unsigned|NO||
||attemptTimes|尝试登录失败次数|int(10) unsigned|NO|0|
||lastAttemped|上一次尝试时间戳|timestamp|NO|CURRENT_TIMESTAMP|
||lastLocked|上一次锁定时间|datetime|YES||
||lastLoginIP|上一次尝试登录ip|int(10)|YES||
|
