这是跟着 spring 的入门指引写的一个 RESTful Web Service 

[原文链接](https://spring.io/guides/gs/rest-service/)

## 可能有用的文档

[Annotation Type RestController](https://docs.spring.io/spring/docs/current/javadoc-api/org/springframework/web/bind/annotation/RestController.html)

[gradle 文档](https://docs.gradle.org/current/userguide/userguide.html)

## 踩坑指南

- gradle 无法找到主类：在 `./build.gradle` 中的 `bootJar` 里面引入键 `mainClassName` ，在此键的值中指定主类的完全限定名 `hello.Application` 。参考文档：[Class BootJar](https://docs.spring.io/spring-boot/docs/current/gradle-plugin/api/org/springframework/boot/gradle/tasks/bundling/BootJar.html)

# What's more

[spring-guides/gs-rest-service](https://github.com/spring-guides/gs-rest-service)

