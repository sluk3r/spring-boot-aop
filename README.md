# Spring Boot Aspect Oriented Programming (AOP) 实例



This is a small TODO-list example application that shows how to create Aspect that handle cross-cutting concerns. It demonstrates 2 different Aspects:

* TimeLogAspect: an aspect applied through the @Timed annotation that logs the duration of a method call
* RestrictAspect: an aspect that restricts method access through a @Restrict annotation

A blog post explaining more can be found at [Spring Aop实例简介--基于Spring Boot实现（一）：初步介绍](https://mp.weixin.qq.com/s/eFUiSD8YCqXVpFqpLfn7ag)和
