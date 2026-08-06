---
title: EventStoreDB
categories:
  - nosql-database
docs:
  - id: nodejs
    url: https://node.testcontainers.org/modules/kurrentdb/
    maintainer: core
    example: |
      ```javascript
      const container = await new KurrentDbContainer("kurrentplatform/kurrentdb:26.1").start();
      ```
    installation: |
      ```bash
      npm install @testcontainers/kurrentdb --save-dev
      ```
description: |
  EventStoreDB is an event sourcing database that stores data in streams of immutable events.
---
