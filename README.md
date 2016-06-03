# Bang_login
运行说明：
没有连接数据库，用一个数组DUMMY_CREDENTIALS模拟，已经存在三个用户：{
            "user1@qq.com:test1", "user2@qq.com:test2",
            "user3@qq.com:test3"
    };
用这三个帐号可以登录。

# 修改说明
添加了两个activity和对用layout
  login.java
  register.java    
  activity_login.xml
  content_login.xml
  activity_register.xml
  content_register.xml
-------------------
整合说明: 没有其他依赖，把以上文件复制进当前项目就可以了

和数据库连接的部分用TODO标记出来了，可以直接查看。
1- 登录部分连接数据库获取用户名和密码，回到“我”的界面时更新用户信息
2- 注册部分，检查用户名是否存在，添加用户名 密码 用户信息到数据库中
