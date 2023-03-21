---
title: "sqlmap"
date: 2023-03-09
draft: false
---

OSCP考试禁止使用



```bash
# sqlmap -u http://localhost:8081/?id=1 --dump-all --exclude-sysdbs
--dump-all：查找并转储找到的所有数据库
--exclude-sysdbs：不会在默认数据库上浪费时间
```

