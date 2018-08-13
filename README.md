# springboot-shiro-v1.2.0
spring boot + mybatis + shiro + layui 搭建的后台权限管理系统  

**支持功能:** 

* 认证

* 授权

* rememberMe(记住我)

* 密码输错次数过多,暂停使用该账户

* 统一异常处理


登录账号: wyait

登录手机号: 18516596566

登录密码: 654321

手机验证码: 181907

这些数据在 wyait.spl 中都有.

![image](https://github.com/haoxiaoyong1014/springboot-shiro-v1.2.0/raw/master/src/main/java/com/wyait/manage/images/wyait.jpeg)

启动项目: 访问: http://localhost:8077/login 会看到如下界面:

![image](https://github.com/haoxiaoyong1014/springboot-shiro-v1.2.0/raw/master/src/main/java/com/wyait/manage/images/s4.jpg)

输入上面的账号密码以及验证码之后点击登录: 

![image](https://github.com/haoxiaoyong1014/springboot-shiro-v1.2.0/raw/master/src/main/java/com/wyait/manage/images/s3.jpeg)

其他不做详细说明,这里只列出重要几个类,其他详见代码:  

<a href="https://github.com/haoxiaoyong1014/springboot-shiro-v1.2.0/blob/master/src/main/java/com/wyait/manage/web/user/AuthController.java">AuthController</a>

<a href="https://github.com/haoxiaoyong1014/springboot-shiro-v1.2.0/blob/master/src/main/java/com/wyait/manage/web/user/UserController.java">UserController</a>

<a href="https://github.com/haoxiaoyong1014/springboot-shiro-v1.2.0/blob/master/src/main/java/com/wyait/manage/config/ShiroConfig.java">ShiroConfig</a>

<a href="https://github.com/haoxiaoyong1014/springboot-shiro-v1.2.0/blob/master/src/main/java/com/wyait/manage/shiro/ShiroRealm.java">ShiroRealm</a>


**尊重原创, 此项目借鉴与: http://blog.51cto.com/wyait/2082803** 


