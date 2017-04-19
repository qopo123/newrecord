# newrecord
## new record用到的技术
1.技术框架

Java 1.7
Spring 4.3.6
Spring MVC
Spring Session 1.3.0
Shiro 1.3.2
Mybatis
Mybatis Plus2.0.5 (Mybatis 通用CRUD框架)
druid1.0.27
dubbox 2.8.4(dubbo有不少坑，换为dubbox，需要本地maven install)
zookeeper client 0.10
slf4j 1.7.23
logback 1.2.1
guava 21.0
rabbitMQ(后续引入)
disconf(后续引入，尚未决定)
redis
zookeeper
2.模块说明

common 公共模块，包含需要web层使用的服务接口以及其他服务模块调用的API接口
service-sys 系统模块，系统管理相关，登录、用户、角色、权限、系统日志等等
service-record档案服务
service-transfile文档转换服务
service-sign 签名服务
service-filescan (后续) 文件扫描模块
service-search(后续) 搜索模块
web web请求模块，主要包含controller层代码
