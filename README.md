## 往事社区

## 资料
[Spring 文档](https://spring.io/guides)
[Github 授权](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)
[Mybatis](http://mybatis.org/spring-boot-starter/mybatis-spring-boot-autoconfigure/)

## 工具
[Bootstrap](https://v3.bootcss.com/getting-started/)
[OkHttp](https://square.github.io/okhttp/)

##
```sql
create table USER
(
	ID INT auto_increment,
	ACCOUNT_ID VARCHAR(100),
	NAME VARCHAR(50),
	TOKEN CHAR(36),
	GMT_CREATE BIGINT,
	GMT_MODIFIED BIGINT,
	constraint USER_2_PK
	primary key (ID)
);



```