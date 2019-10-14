# Docs4dev
https://www.docs4dev.com 

## 项目背景

在开发中，一份文档是必不可少的，但是现在很多的框架，都只有英文版，这对于新手来说非常不友好；虽然国内也有许多人组织翻译，但是这个工作量是非常巨大的，而且时效性没那么高，很多框架的中文文档都是比较老的版本，同时，翻译的文档也很不是那么齐全。基于此，我创建了这个项目，并建立了相关的网站 [Docs4dev](https://www.docs4dev.com )。我会使用爬虫从官方拉取最新版本的文档，并通过调用 **翻译API** 对文档进行初步翻译，以减少后续人工翻译的工作量。

但是，因个人的时间及精力有限，同时我还要维护网站，抓取文档，所以无法及时对所有文档进行一一进行校对，所以，希望你能够帮助我一起来完善文档（[查看校对指南](GUIDE.md)）。

最后，如果你觉得本项目对你有所帮助，希望点赞支持一下。

## 项目技术

目前网站是使用 `Spring Boot` 提供 API， `Nextjs + antd + React Hooks` 做服务端渲染的形式开发的。同时，因为网站的前端使用了很多 h5 特性，所以**对于 IE 的支持不是很友好**，所以推荐使用 `Chrome` 进行访问。

所用技术整理如下：

- **Rest API：**`Spring Boot`
- **服务端渲染：**`nextjs`
- **UI 库：** `antd`
- **编程语言：** `typescript + java`
- **编辑器：**
  - `EasyMD`
  - `stackedit（Vue）`
- **文本对比：** 
  - `diff`
  - `diff2html`
- **全文检索：** `Elasticsearch`

## 参与贡献

- 如果你希望参与校对，请阅读 [校对指南](GUIDE.md)。

- 如果你希望添加某个文档，

- 如果你发现了网站的 bug，
- 如果你觉得网站有哪个可以改进的地方，
- 如果你希望添加更多的工具，
- 请给我提 [issue](https://github.com/docs4dev/docs4dev/issues/new)  😄 。

## 网站新日志

- 2019-10-14 编辑器添加自动保存功能 (https://github.com/docs4dev/docs4dev/issues/10）
- 2019-10-10 修复 GitHub 网站使用github 登录出错 (https://github.com/docs4dev/docs4dev/issues/9)
- 2019-10-03 修复文档翻译错误 (https://github.com/docs4dev/docs4dev/issues/8)
- 2019-08-09 修复网站 502 错误 (https://github.com/docs4dev/docs4dev/issues/5)
- ...

## Roadmap

- 更多文档的支持
- 文档全文 PDF 下载
- [asciidoctor](https://github.com/asciidoctor/asciidoctor) 格式支持
- 移动端（小程序）的支持
- ...
## 文档列表

#### Spring
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [Spring Boot Reference](https://www.docs4dev.com/docs/en/spring-boot/1.5.9.RELEASE/reference) | [1.5.9.RELEASE](https://www.docs4dev.com/docs/en/spring-boot/1.5.9.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-boot/1.5.9.RELEASE/reference) |
| [Spring Boot 中文文档](https://www.docs4dev.com/docs/zh/spring-boot/1.5.9.RELEASE/reference) | [1.5.9.RELEASE](https://www.docs4dev.com/docs/zh/spring-boot/1.5.9.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-boot/1.5.9.RELEASE/reference) |
| [Spring Boot Reference](https://www.docs4dev.com/docs/en/spring-boot/2.1.1.RELEASE/reference) | [2.1.1.RELEASE](https://www.docs4dev.com/docs/en/spring-boot/2.1.1.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-boot/2.1.1.RELEASE/reference) |
| [Spring Boot 中文文档](https://www.docs4dev.com/docs/zh/spring-boot/2.1.1.RELEASE/reference) | [2.1.1.RELEASE](https://www.docs4dev.com/docs/zh/spring-boot/2.1.1.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-boot/2.1.1.RELEASE/reference) |
| [Spring Cloud Reference](https://www.docs4dev.com/docs/en/spring-cloud/Edgware.SR5/reference) | [Edgware.SR5](https://www.docs4dev.com/docs/en/spring-cloud/Edgware.SR5/reference) | [English](https://www.docs4dev.com/docs/en/spring-cloud/Edgware.SR5/reference) |
| [Spring Cloud 中文文档](https://www.docs4dev.com/docs/zh/spring-cloud/Edgware.SR5/reference) | [Edgware.SR5](https://www.docs4dev.com/docs/zh/spring-cloud/Edgware.SR5/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-cloud/Edgware.SR5/reference) |
| [Spring Cloud Reference](https://www.docs4dev.com/docs/en/spring-cloud/Finchley.SR2/reference) | [Finchley.SR2](https://www.docs4dev.com/docs/en/spring-cloud/Finchley.SR2/reference) | [English](https://www.docs4dev.com/docs/en/spring-cloud/Finchley.SR2/reference) |
| [Spring Cloud 中文文档](https://www.docs4dev.com/docs/zh/spring-cloud/Finchley.SR2/reference) | [Finchley.SR2](https://www.docs4dev.com/docs/zh/spring-cloud/Finchley.SR2/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-cloud/Finchley.SR2/reference) |
| [Spring Cloud Reference](https://www.docs4dev.com/docs/en/spring-cloud/Greenwich.RELEASE/reference) | [Greenwich.RELEASE](https://www.docs4dev.com/docs/en/spring-cloud/Greenwich.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-cloud/Greenwich.RELEASE/reference) |
| [Spring Cloud 中文文档](https://www.docs4dev.com/docs/zh/spring-cloud/Greenwich.RELEASE/reference) | [Greenwich.RELEASE](https://www.docs4dev.com/docs/zh/spring-cloud/Greenwich.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-cloud/Greenwich.RELEASE/reference) |
| [Spring Batch Reference](https://www.docs4dev.com/docs/en/spring-batch/3.0.x/reference) | [3.0.x](https://www.docs4dev.com/docs/en/spring-batch/3.0.x/reference) | [English](https://www.docs4dev.com/docs/en/spring-batch/3.0.x/reference) |
| [Spring Batch 中文文档](https://www.docs4dev.com/docs/zh/spring-batch/3.0.x/reference) | [3.0.x](https://www.docs4dev.com/docs/zh/spring-batch/3.0.x/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-batch/3.0.x/reference) |
| [Spring Batch Reference](https://www.docs4dev.com/docs/en/spring-batch/4.1.x/reference) | [4.1.x](https://www.docs4dev.com/docs/en/spring-batch/4.1.x/reference) | [English](https://www.docs4dev.com/docs/en/spring-batch/4.1.x/reference) |
| [Spring Batch 中文文档](https://www.docs4dev.com/docs/zh/spring-batch/4.1.x/reference) | [4.1.x](https://www.docs4dev.com/docs/zh/spring-batch/4.1.x/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-batch/4.1.x/reference) |
| [Spring Session Reference](https://www.docs4dev.com/docs/en/spring-session/1.3.4.RELEASE/reference) | [1.3.4.RELEASE](https://www.docs4dev.com/docs/en/spring-session/1.3.4.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-session/1.3.4.RELEASE/reference) |
| [Spring Session 中文文档](https://www.docs4dev.com/docs/zh/spring-session/1.3.4.RELEASE/reference) | [1.3.4.RELEASE](https://www.docs4dev.com/docs/zh/spring-session/1.3.4.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-session/1.3.4.RELEASE/reference) |
| [Spring Session Reference](https://www.docs4dev.com/docs/en/spring-session/2.1.2.RELEASE/reference) | [2.1.2.RELEASE](https://www.docs4dev.com/docs/en/spring-session/2.1.2.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-session/2.1.2.RELEASE/reference) |
| [Spring Session 中文文档](https://www.docs4dev.com/docs/zh/spring-session/2.1.2.RELEASE/reference) | [2.1.2.RELEASE](https://www.docs4dev.com/docs/zh/spring-session/2.1.2.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-session/2.1.2.RELEASE/reference) |
| [Spring Security Reference](https://www.docs4dev.com/docs/en/spring-security/4.2.10.RELEASE/reference) | [4.2.10.RELEASE](https://www.docs4dev.com/docs/en/spring-security/4.2.10.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-security/4.2.10.RELEASE/reference) |
| [Spring Security 中文文档](https://www.docs4dev.com/docs/zh/spring-security/4.2.10.RELEASE/reference) | [4.2.10.RELEASE](https://www.docs4dev.com/docs/zh/spring-security/4.2.10.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-security/4.2.10.RELEASE/reference) |
| [Spring Security Reference](https://www.docs4dev.com/docs/en/spring-security/5.1.2.RELEASE/reference) | [5.1.2.RELEASE](https://www.docs4dev.com/docs/en/spring-security/5.1.2.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-security/5.1.2.RELEASE/reference) |
| [Spring Security 中文文档](https://www.docs4dev.com/docs/zh/spring-security/5.1.2.RELEASE/reference) | [5.1.2.RELEASE](https://www.docs4dev.com/docs/zh/spring-security/5.1.2.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-security/5.1.2.RELEASE/reference) |
| [Spring AMQP Reference](https://www.docs4dev.com/docs/en/spring-amqp/1.7.11.RELEASE/reference) | [1.7.11.RELEASE](https://www.docs4dev.com/docs/en/spring-amqp/1.7.11.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-amqp/1.7.11.RELEASE/reference) |
| [Spring AMQP 中文文档](https://www.docs4dev.com/docs/zh/spring-amqp/1.7.11.RELEASE/reference) | [1.7.11.RELEASE](https://www.docs4dev.com/docs/zh/spring-amqp/1.7.11.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-amqp/1.7.11.RELEASE/reference) |
| [Spring AMQP Reference](https://www.docs4dev.com/docs/en/spring-amqp/2.1.2.RELEASE/reference) | [2.1.2.RELEASE](https://www.docs4dev.com/docs/en/spring-amqp/2.1.2.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-amqp/2.1.2.RELEASE/reference) |
| [Spring AMQP 中文文档](https://www.docs4dev.com/docs/zh/spring-amqp/2.1.2.RELEASE/reference) | [2.1.2.RELEASE](https://www.docs4dev.com/docs/zh/spring-amqp/2.1.2.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-amqp/2.1.2.RELEASE/reference) |
| [Spring Framework Reference](https://www.docs4dev.com/docs/en/spring-framework/4.3.21.RELEASE/reference) | [4.3.21.RELEASE](https://www.docs4dev.com/docs/en/spring-framework/4.3.21.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-framework/4.3.21.RELEASE/reference) |
| [Spring Framework 中文文档](https://www.docs4dev.com/docs/zh/spring-framework/4.3.21.RELEASE/reference) | [4.3.21.RELEASE](https://www.docs4dev.com/docs/zh/spring-framework/4.3.21.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-framework/4.3.21.RELEASE/reference) |
| [Spring Framework Reference](https://www.docs4dev.com/docs/en/spring-framework/5.1.3.RELEASE/reference) | [5.1.3.RELEASE](https://www.docs4dev.com/docs/en/spring-framework/5.1.3.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-framework/5.1.3.RELEASE/reference) |
| [Spring Framework 中文文档](https://www.docs4dev.com/docs/zh/spring-framework/5.1.3.RELEASE/reference) | [5.1.3.RELEASE](https://www.docs4dev.com/docs/zh/spring-framework/5.1.3.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-framework/5.1.3.RELEASE/reference) |
| [Spring Data JDBC](https://www.docs4dev.com/docs/en/spring-data-jdbc/1.0.5.RELEASE/reference) | [1.0.5.RELEASE](https://www.docs4dev.com/docs/en/spring-data-jdbc/1.0.5.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-data-jdbc/1.0.5.RELEASE/reference) |
| [Spring Data JDBC](https://www.docs4dev.com/docs/zh/spring-data-jdbc/1.0.5.RELEASE/reference) | [1.0.5.RELEASE](https://www.docs4dev.com/docs/zh/spring-data-jdbc/1.0.5.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-data-jdbc/1.0.5.RELEASE/reference) |
| [Spring Data JPA](https://www.docs4dev.com/docs/en/spring-data-jpa/1.11.18.RELEASE/reference) | [1.11.18.RELEASE](https://www.docs4dev.com/docs/en/spring-data-jpa/1.11.18.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-data-jpa/1.11.18.RELEASE/reference) |
| [Spring Data JPA](https://www.docs4dev.com/docs/zh/spring-data-jpa/1.11.18.RELEASE/reference) | [1.11.18.RELEASE](https://www.docs4dev.com/docs/zh/spring-data-jpa/1.11.18.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-data-jpa/1.11.18.RELEASE/reference) |
| [Spring Data JPA](https://www.docs4dev.com/docs/en/spring-data-jpa/2.0.13.RELEASE/reference) | [2.0.13.RELEASE](https://www.docs4dev.com/docs/en/spring-data-jpa/2.0.13.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-data-jpa/2.0.13.RELEASE/reference) |
| [Spring Data JPA](https://www.docs4dev.com/docs/zh/spring-data-jpa/2.0.13.RELEASE/reference) | [2.0.13.RELEASE](https://www.docs4dev.com/docs/zh/spring-data-jpa/2.0.13.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-data-jpa/2.0.13.RELEASE/reference) |
| [Spring Data JPA](https://www.docs4dev.com/docs/en/spring-data-jpa/2.1.5.RELEASE/reference) | [2.1.5.RELEASE](https://www.docs4dev.com/docs/en/spring-data-jpa/2.1.5.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-data-jpa/2.1.5.RELEASE/reference) |
| [Spring Data JPA](https://www.docs4dev.com/docs/zh/spring-data-jpa/2.1.5.RELEASE/reference) | [2.1.5.RELEASE](https://www.docs4dev.com/docs/zh/spring-data-jpa/2.1.5.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-data-jpa/2.1.5.RELEASE/reference) |
| [Spring Data Redis](https://www.docs4dev.com/docs/en/spring-data-redis/1.8.18.RELEASE/reference) | [1.8.18.RELEASE](https://www.docs4dev.com/docs/en/spring-data-redis/1.8.18.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-data-redis/1.8.18.RELEASE/reference) |
| [Spring Data Redis](https://www.docs4dev.com/docs/zh/spring-data-redis/1.8.18.RELEASE/reference) | [1.8.18.RELEASE](https://www.docs4dev.com/docs/zh/spring-data-redis/1.8.18.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-data-redis/1.8.18.RELEASE/reference) |
| [Spring Data Redis](https://www.docs4dev.com/docs/en/spring-data-redis/2.1.5.RELEASE/reference) | [2.1.5.RELEASE](https://www.docs4dev.com/docs/en/spring-data-redis/2.1.5.RELEASE/reference) | [English](https://www.docs4dev.com/docs/en/spring-data-redis/2.1.5.RELEASE/reference) |
| [Spring Data Redis](https://www.docs4dev.com/docs/zh/spring-data-redis/2.1.5.RELEASE/reference) | [2.1.5.RELEASE](https://www.docs4dev.com/docs/zh/spring-data-redis/2.1.5.RELEASE/reference) | [中文](https://www.docs4dev.com/docs/zh/spring-data-redis/2.1.5.RELEASE/reference) |


#### Http Server
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [Nginx](https://www.docs4dev.com/docs/en/nginx/current/reference) | [current](https://www.docs4dev.com/docs/en/nginx/current/reference) | [English](https://www.docs4dev.com/docs/en/nginx/current/reference) |
| [Nginx 中文文档](https://www.docs4dev.com/docs/zh/nginx/current/reference) | [current](https://www.docs4dev.com/docs/zh/nginx/current/reference) | [中文](https://www.docs4dev.com/docs/zh/nginx/current/reference) |
| [Apache](https://www.docs4dev.com/docs/en/apache/2.4/reference) | [2.4](https://www.docs4dev.com/docs/en/apache/2.4/reference) | [English](https://www.docs4dev.com/docs/en/apache/2.4/reference) |
| [Apache 中文文档](https://www.docs4dev.com/docs/zh/apache/2.4/reference) | [2.4](https://www.docs4dev.com/docs/zh/apache/2.4/reference) | [中文](https://www.docs4dev.com/docs/zh/apache/2.4/reference) |


#### Python
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [Python](https://www.docs4dev.com/docs/en/python/2.7.15/all) | [2.7.15](https://www.docs4dev.com/docs/en/python/2.7.15/all) | [English](https://www.docs4dev.com/docs/en/python/2.7.15/all) |
| [Python 中文文档](https://www.docs4dev.com/docs/zh/python/2.7.15/all) | [2.7.15](https://www.docs4dev.com/docs/zh/python/2.7.15/all) | [中文](https://www.docs4dev.com/docs/zh/python/2.7.15/all) |
| [Python](https://www.docs4dev.com/docs/en/python/3.7.2rc1/all) | [3.7.2rc1](https://www.docs4dev.com/docs/en/python/3.7.2rc1/all) | [English](https://www.docs4dev.com/docs/en/python/3.7.2rc1/all) |
| [Python 中文文档](https://www.docs4dev.com/docs/zh/python/3.7.2rc1/all) | [3.7.2rc1](https://www.docs4dev.com/docs/zh/python/3.7.2rc1/all) | [中文](https://www.docs4dev.com/docs/zh/python/3.7.2rc1/all) |


#### Database
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [MySql](https://www.docs4dev.com/docs/en/mysql/5.7/reference) | [5.7](https://www.docs4dev.com/docs/en/mysql/5.7/reference) | [English](https://www.docs4dev.com/docs/en/mysql/5.7/reference) |
| [MySql 中文文档](https://www.docs4dev.com/docs/zh/mysql/5.7/reference) | [5.7](https://www.docs4dev.com/docs/zh/mysql/5.7/reference) | [中文](https://www.docs4dev.com/docs/zh/mysql/5.7/reference) |
| [PostgreSQL Documentation](https://www.docs4dev.com/docs/en/postgre-sql/10.7/reference) | [10.7](https://www.docs4dev.com/docs/en/postgre-sql/10.7/reference) | [English](https://www.docs4dev.com/docs/en/postgre-sql/10.7/reference) |
| [PostgreSQL 中文文档](https://www.docs4dev.com/docs/zh/postgre-sql/10.7/reference) | [10.7](https://www.docs4dev.com/docs/zh/postgre-sql/10.7/reference) | [中文](https://www.docs4dev.com/docs/zh/postgre-sql/10.7/reference) |
| [PostgreSQL Documentation](https://www.docs4dev.com/docs/en/postgre-sql/11.2/reference) | [11.2](https://www.docs4dev.com/docs/en/postgre-sql/11.2/reference) | [English](https://www.docs4dev.com/docs/en/postgre-sql/11.2/reference) |
| [PostgreSQL 中文文档](https://www.docs4dev.com/docs/zh/postgre-sql/11.2/reference) | [11.2](https://www.docs4dev.com/docs/zh/postgre-sql/11.2/reference) | [中文](https://www.docs4dev.com/docs/zh/postgre-sql/11.2/reference) |
| [OpenTSDB](https://www.docs4dev.com/docs/en/opentsdb/2.3/reference) | [2.3](https://www.docs4dev.com/docs/en/opentsdb/2.3/reference) | [English](https://www.docs4dev.com/docs/en/opentsdb/2.3/reference) |
| [OpenTSDB 中文文档](https://www.docs4dev.com/docs/zh/opentsdb/2.3/reference) | [2.3](https://www.docs4dev.com/docs/zh/opentsdb/2.3/reference) | [中文](https://www.docs4dev.com/docs/zh/opentsdb/2.3/reference) |
| [Mongodb Manual](https://www.docs4dev.com/docs/en/mongodb/v3.6/reference) | [v3.6](https://www.docs4dev.com/docs/en/mongodb/v3.6/reference) | [English](https://www.docs4dev.com/docs/en/mongodb/v3.6/reference) |
| [Mongodb 中文文档](https://www.docs4dev.com/docs/zh/mongodb/v3.6/reference) | [v3.6](https://www.docs4dev.com/docs/zh/mongodb/v3.6/reference) | [中文](https://www.docs4dev.com/docs/zh/mongodb/v3.6/reference) |


#### Logging
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [Log4j2 Manual](https://www.docs4dev.com/docs/en/log4j2/2.x/all) | [2.x](https://www.docs4dev.com/docs/en/log4j2/2.x/all) | [English](https://www.docs4dev.com/docs/en/log4j2/2.x/all) |
| [Log4j2 中文文档](https://www.docs4dev.com/docs/zh/log4j2/2.x/all) | [2.x](https://www.docs4dev.com/docs/zh/log4j2/2.x/all) | [中文](https://www.docs4dev.com/docs/zh/log4j2/2.x/all) |
| [Logback Manual](https://www.docs4dev.com/docs/en/logback/1.3.0-alpha4/reference) | [1.3.0-alpha4](https://www.docs4dev.com/docs/en/logback/1.3.0-alpha4/reference) | [English](https://www.docs4dev.com/docs/en/logback/1.3.0-alpha4/reference) |
| [Logback 中文文档](https://www.docs4dev.com/docs/zh/logback/1.3.0-alpha4/reference) | [1.3.0-alpha4](https://www.docs4dev.com/docs/zh/logback/1.3.0-alpha4/reference) | [中文](https://www.docs4dev.com/docs/zh/logback/1.3.0-alpha4/reference) |


#### ORM
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [Hibernate ORM User Guide](https://www.docs4dev.com/docs/en/hibernate-orm/5.4/reference) | [5.4](https://www.docs4dev.com/docs/en/hibernate-orm/5.4/reference) | [English](https://www.docs4dev.com/docs/en/hibernate-orm/5.4/reference) |
| [Hibernate ORM 用户指南](https://www.docs4dev.com/docs/zh/hibernate-orm/5.4/reference) | [5.4](https://www.docs4dev.com/docs/zh/hibernate-orm/5.4/reference) | [中文](https://www.docs4dev.com/docs/zh/hibernate-orm/5.4/reference) |


#### Template engine
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [Thymeleaf Tutorial](https://www.docs4dev.com/docs/en/thymeleaf/3.0/reference) | [3.0](https://www.docs4dev.com/docs/en/thymeleaf/3.0/reference) | [English](https://www.docs4dev.com/docs/en/thymeleaf/3.0/reference) |
| [Thymeleaf 教程](https://www.docs4dev.com/docs/zh/thymeleaf/3.0/reference) | [3.0](https://www.docs4dev.com/docs/zh/thymeleaf/3.0/reference) | [中文](https://www.docs4dev.com/docs/zh/thymeleaf/3.0/reference) |
| [Apache FreeMarker Manual](https://www.docs4dev.com/docs/en/freemarker/2.3.28/reference) | [2.3.28](https://www.docs4dev.com/docs/en/freemarker/2.3.28/reference) | [English](https://www.docs4dev.com/docs/en/freemarker/2.3.28/reference) |
| [Apache FreeMarker 中文手册](https://www.docs4dev.com/docs/zh/freemarker/2.3.28/reference) | [2.3.28](https://www.docs4dev.com/docs/zh/freemarker/2.3.28/reference) | [中文](https://www.docs4dev.com/docs/zh/freemarker/2.3.28/reference) |


#### Big Data
| 名称 | 文档版本 | 语言 |
| ---- | ---- | ---- |
| [Apache Flume User Guide](https://www.docs4dev.com/docs/en/flume/1.9.0/reference) | [1.9.0](https://www.docs4dev.com/docs/en/flume/1.9.0/reference) | [English](https://www.docs4dev.com/docs/en/flume/1.9.0/reference) |
| [Apache Flume 用户指南](https://www.docs4dev.com/docs/zh/flume/1.9.0/reference) | [1.9.0](https://www.docs4dev.com/docs/zh/flume/1.9.0/reference) | [中文](https://www.docs4dev.com/docs/zh/flume/1.9.0/reference) |
| [Apache Hive Language Manual](https://www.docs4dev.com/docs/en/apache-hive/3.1.1/reference) | [3.1.1](https://www.docs4dev.com/docs/en/apache-hive/3.1.1/reference) | [English](https://www.docs4dev.com/docs/en/apache-hive/3.1.1/reference) |
| [Apache Hive 中文手册](https://www.docs4dev.com/docs/zh/apache-hive/3.1.1/reference) | [3.1.1](https://www.docs4dev.com/docs/zh/apache-hive/3.1.1/reference) | [中文](https://www.docs4dev.com/docs/zh/apache-hive/3.1.1/reference) |
