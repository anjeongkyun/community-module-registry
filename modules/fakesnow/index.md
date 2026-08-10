---
title: fakesnow
categories:
  - relational-database
docs:
  - id: java
    url: https://github.com/anjeongkyun/testcontainers-fakesnow
    maintainer: community
    example: |
      ```java
      var fakesnow = new FakeSnowContainer();
      fakesnow.start();
      ```
    installation: |
      ```xml
      <dependency>
          <groupId>io.github.anjeongkyun</groupId>
          <artifactId>testcontainers-fakesnow</artifactId>
          <version>0.1.0</version>
          <scope>test</scope>
      </dependency>
      ```
description: |
  fakesnow runs a local fake of Snowflake, backed by DuckDB, that the official snowflake-jdbc driver connects to unmodified. It lets JVM projects test Snowflake-flavoured SQL — VARIANT, LATERAL FLATTEN, QUALIFY — without a Snowflake account.
---
