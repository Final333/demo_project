insertUser
===
* 插入数据
insert into test_user(id,name,phone,title,email,gender,date_of_birth
    ,sys_create_time,sys_create_user,sys_update_time,sys_update_user)
values (#id#,#name#,#phone#,#title#,#email#,#gender#,#dateOfBirth#
    ,#sysCreateTime#,#sysCreateUser#,#sysUpdateTime#,#sysUpdateUser#)

cleanUser
===
*清空目标表
DELETE FROM test_user