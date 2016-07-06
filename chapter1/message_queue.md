#message_queue
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|UUID|varchar(100)|NO||
||mobile_num|要发送短信的手机号码|varchar(20)|YES||
||sms_content|要发送短信的内容|text|YES||
||user_id|要发送站内信的用户ID|int(11)|YES||
||inner_mail_content|站内信的内容|text|YES||
||inner_mail_type|站内信类型|varchar(200)|YES||
||e_mail|电子邮件|varchar(200)|YES||
||e_mail_title|要发送邮件的标题|text|YES||
||mail_content|邮件内容|text|YES||
||mail_type|邮件类型|varchar(200)|YES||
||_status|消息的状态 0待发送 1已发送|int(2)|NO|0|
||send_time|发送时间|datetime|YES||
||create_time|创建时间|datetime|YES||
|
