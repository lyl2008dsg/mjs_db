#common_news_info
* 网站通用新闻信息
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|ID|ID|int(11)|NO||
||TITLE|标题|varchar(200)|YES||
|MUL|BELONG_TYPE|所属类型|varchar(20)|YES||
||ARTICLE_SOURCE|文章来源|varchar(1000)|YES||
||AUTHOR|作者|varchar(200)|YES||
||ISSUE_TIME|发布时间|datetime|YES||
||STATE|状态|varchar(20)|NO|1|
||RANK|排序|decimal(5,0)|YES||
||CONTENT_BRIEF|内容简介|varchar(2000)|YES||
||CONTENT|内容|text|YES||
||LAST_UPDATE_USER|最后修改用户|varchar(200)|YES||
||LAST_UPDATE_TIME|最后修改时间|datetime|YES||
||imgName|文章图片名|varchar(50)|YES||
||useIn||varchar(10)|YES||
|
