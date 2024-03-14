---
title: "ifconfig command page"
description: "configure a network interface"
---
## ifconfig
**Description:** configure a network interface<br>
**Example output:**
```sh
enp0s31f6: flags=4099<UP,BROADCAST,MULTICAST>  mtu 1500
        ether c8:5b:76:29:f1:55  txqueuelen 1000  (Ethernet)
        RX packets 0  bytes 0 (0.0 B)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 0  bytes 0 (0.0 B)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
        device interrupt 16  memory 0xf1200000-f1220000  

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 26859  bytes 50550300 (48.2 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 26859  bytes 50550300 (48.2 MiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

wlp4s0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 192.168.75.101  netmask 255.255.255.0  broadcast 192.168.75.255
        inet6 fe80::c5d5:40da:f664:cf8e  prefixlen 64  scopeid 0x20<link>
        ether e4:b3:18:b5:1d:f5  txqueuelen 1000  (Ethernet)
        RX packets 403594  bytes 474527430 (452.5 MiB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 189327  bytes 55161270 (52.6 MiB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```
