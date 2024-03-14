---
title: "dig command page"
description: "DNS lookup utility"
---
## dig
**Description:** DNS lookup utility<br>
**Example output:**
```sh

; <<>> DiG 9.18.24 <<>>
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 50918
;; flags: qr rd ra; QUERY: 1, ANSWER: 13, AUTHORITY: 0, ADDITIONAL: 1

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 4096
; COOKIE: 5a615726fdf5ac1f82696d6165e73b43869a18aed1394e19 (good)
;; QUESTION SECTION:
;.				IN	NS

;; ANSWER SECTION:
.			505524	IN	NS	m.root-servers.net.
.			505524	IN	NS	c.root-servers.net.
.			505524	IN	NS	i.root-servers.net.
.			505524	IN	NS	g.root-servers.net.
.			505524	IN	NS	a.root-servers.net.
.			505524	IN	NS	f.root-servers.net.
.			505524	IN	NS	l.root-servers.net.
.			505524	IN	NS	b.root-servers.net.
.			505524	IN	NS	e.root-servers.net.
.			505524	IN	NS	j.root-servers.net.
.			505524	IN	NS	h.root-servers.net.
.			505524	IN	NS	k.root-servers.net.
.			505524	IN	NS	d.root-servers.net.

;; Query time: 56 msec
;; SERVER: 192.168.75.1#53(192.168.75.1) (UDP)
;; WHEN: Tue Mar 05 16:33:22 +01 2024
;; MSG SIZE  rcvd: 267
```
