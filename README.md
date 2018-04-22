# 环境


开发工具：IntelliJ IDEA

数据库：MySQL 5.7

JDK：1.8

构建工具：Maven


# 开始

- 使用 Git 将仓库 develop 分支克隆到本地
- 安装 JDK, Git, MySQL 
- 打开 IntelliJ IDEA，open existing project 导入项目
- 运行 me.zbl.HospitalApplication
- 浏览器访问 http://localhost:8086
- 系统登录：用户名 admin，密码 123456

# 其他

- 数据库 IP：47.93.187.44，端口 3306
- 数据库用户名：dev，密码：19961120，该用户目前权限有：SELECT, INSERT, UPDATE
- IDEA 激活可以使用我的 License Server，地址：http://jetbrains.letec.top
- 药品管理系统用到的表前缀为：app_，其他前缀的表为项目必须，但系统非必须，无需修改
- 新增数据表以前缀 app_ 开头，避免与其他表表淆
- 目前服务器上的数据库结构是我的设计，可以使用任意 GUI 工具修改现有表或新建表
- 系统使用的 ORM 框架为 MyBatis，可以使用 Spring Data JPA


# 可能有用的东西

- [Building an Application with Spring Boot](https://spring.io/guides/gs/spring-boot/)
- [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
- [Spring Data JPA Guide](https://spring.io/guides/gs/accessing-data-jpa/)
