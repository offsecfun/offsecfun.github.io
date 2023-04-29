---
title: "2. 提权"
draft: false
weight: 20
---

获得低权限后，如何获得root权限呢



```bash
python -c 'import pty; pty.spawn("/bin/bash")' 
```

