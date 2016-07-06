#disclosuer_menu
* -
 
|是否主键	|字段名	|字段描述	|数据类型	|可空	|缺省	|
| --------|-----|-----|-----|-----|-----|
|PRI|id|信息披露菜单id|int(10)|NO||
||name|菜单名称|varchar(32)|YES||
||status|菜单状态（0正常，1关闭）|int(2)|YES|0|
||isShow|是否前台显示（0显示，1不显示）|int(2)|YES|0|
||staffId|操作人员id|int(10)|YES||
||departmentId|部门id|int(10)|YES||
||createTime|创建时间|datetime|YES||
||updateTime|修改时间|datetime|YES||
||reserve1|备注|varchar(32)|YES||
|
