---
title: JDK JMH基准测试
authors: [xilio]
tags: [JDK, 基准测试]
---

# 2025-05-21 JDK JMH基准测试

## 介绍

> 什么是【基准测试】？基准测试主要用于测试代码在JVM上的性能，例如比较不同算法的性能效率，执行时间，吞吐量，执行效率，多线程性能表现，垃圾回收等等

JMH是openJdk自带的一款代码基准测试工具，具有很高的性能，完全隔离测试环境，使用简单，提供纳秒级别的测试精度，

## 使用
在SpringBoot项目中，通过引入下面的依赖即可继承

```xml
<dependency>
    <groupId>org.openjdk.jmh</groupId>
    <artifactId>jmh-core</artifactId>
    <version>1.36</version>
</dependency>
```



