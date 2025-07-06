---
title: common commands
tags:
---

## PostgreSQL
- brew services start postgresql
- brew services restart postgresql@14
- createdb dbname
- dropdb dbname

- login, 连接到pgsql服务器
  - psql -U username  
  - psql -U username -d 数据库名  
  
  - psql dbname
  - \c 数据库名    切换数据库
  - 随便进入数据库后，  
    - \l \list 查看数据库列表

 但我确实没有用户名，只有Owner

- 帮助
  - mydb=> \h
- 退出
  - mydb=> \q

- 查看数据表
  - \dt

我成功了，需要整理一下笔记，
- Today
  - 配置postgresql
  - 连接postgresql
  - 测试服务器的sql连接

- 新学了什么
  - typeorm
    - 可以去看typeorm的原理 
  - postgresql
    - 可以去记一些SQL语句
下一步是什么