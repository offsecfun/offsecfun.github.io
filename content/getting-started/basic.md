---
title: "基操"
draft: false
weight: 11
---

#### arp-scan

```bash
$ sudo arp-scan -l
```

![](../../images/arp-scan1.webp)

```bash
$ sudo arp-scan 192.168.88.0/24
```

![](../../images/arp-scan2.webp)



#### export

```bash
$ export rip=192.168.88.152
```



#### nmap

```bash
$ sudo nmap -v -A -p- $rip
```

