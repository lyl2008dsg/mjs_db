#disclosuer_info
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|序号|int(10)|NO||
||title|文章标题|varchar(2000)|YES||
||type|文件类型1:文本，2:附件,3:html|int(2)|YES||
||author|作者|varchar(32)|YES||
||issueTime|发布时间|datetime|YES||
||articleSource|文章来源|varchar(200)|YES||
||contentBrief|内容简介|varchar(2000)|YES||
||content|内容|text|YES||
||status|状态0正常1关闭|int(2)|YES|0|
||isShow|显示状态0显示，1不显示|int(2)|YES|0|
||menuId|父菜单id|int(10)|YES||
||staffId|角色id|int(10)|YES||
||departmentId|部门id|int(10)|YES||
||lastUpTime|最后修改时间|datetime|YES||
||reserve1|备用1|varchar(32)|YES||
|
