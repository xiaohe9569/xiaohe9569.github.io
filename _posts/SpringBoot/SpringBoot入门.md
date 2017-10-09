---
layout: post
title: "SpringBoot入门"
categories: [SpringBoot]
description: 入门及框架搭建
keywords: springboot,jpa
---

### 入门

>> 参考：<https://www.zhihu.com/search?type=content&q=spring%20boot>


#### 框架

1、访问http://start.spring.io/ 生成boot项目

2、目录结构


```wiki
com
  +- example
    +- myproject
      +- Application.java
      |
      +- domain
      |  +- Customer.java
      |  +- CustomerRepository.java
      |
      +- service
      |  +- CustomerService.java
      |
      +- controller
      |  +- CustomerController.java
      |
```

1、Application.java 建议放到跟目录下面,主要用于做一些框架配置


2、domain 目录主要用于实体（Entity）与数据访问层（Repository）

3、service 层主要是业务类代码

4、controller 负责页面访问控制

#### web模块

1、pom.xml中添加支持web的模块：

```java
<dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
 </dependency>
```

pom.xml文件中默认有两个模块：

spring-boot-starter：核心模块，包括自动配置支持、日志和YAML；

spring-boot-starter-test：测试模块，包括JUnit、Hamcrest、Mockito。
