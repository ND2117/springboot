项目名称
一个基于 Spring Boot 的快速开发脚手架，提供 RESTful API 接口，集成常用功能，适用于微服务或单体应用快速启动。

技术栈
Java 8

Spring Boot 2.5.4

Maven 3.6+

MySQL数据库

快速开始
克隆项目：git clone https://github.com/ND2117/springboot.git

修改 application.yml 中的数据库连接配置

执行 mvn clean install 构建项目

运行 java -jar target/*.jar 启动应用

访问 http://localhost:8080 查看效果

主要功能
用户认证与授权（JWT）

统一异常处理与日志记录

MyBatis-Plus 数据持久层

Swagger 在线接口文档