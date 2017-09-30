# rest-base
基于spring boot搭建的web基础框架，包含了web开发中常用的功能，如：缓存（redis）、日志、事务、JPA、shiro、安全、常用工具类、swagger2在线接口文档、跨域支持等，可以基于该项目快速进行公司内部的项目开发。

# 运行方式
1. 本地创建数据库base，调整application-local.properties内的mysql和redis配置；
2. 创建数据库后，直接运行BaseApplication，待项目启动后，在数据库内执行doc目录下的init.sql和index.sql;
3. 访问http://localhost:8070/login/submit?username=admin&pwd=admin2017进行登录
4. 访问http://localhost:8070/swagger-ui.html查看接口文档；
5. 访问http://localhost:8070/admin/user/list测试接口；
