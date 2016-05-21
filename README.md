# Bang_login
第一个版本的，添加了登录操作，进入我的界面，点切换帐号，可进入登录界面。

主要看loginActivity，邮箱和密码登录

没有连接数据库，用一个数组DUMMY_CREDENTIALS模拟，已经存在三个用户：{
            "user1@qq.com:test1", "user2@qq.com:test2",
            "user3@qq.com:test3"
    };
用这三个帐号可以登录。

登录成功后返回‘我’的界面，看不出来有什么不同，因为用户名、头像等是在注册时候弄的，TODO:登录成功后可以同步这些。
