```bash
dig -p 53 -x 192.168.43.1 @192.168.43.1
```

[/home/eni9ma/Final/results/192.168.43.1/scans/tcp53/tcp_53_dns_reverse-lookup.txt](file:///home/eni9ma/Final/results/192.168.43.1/scans/tcp53/tcp_53_dns_reverse-lookup.txt):

```

; <<>> DiG 9.19.21-1-Debian <<>> -p 53 -x 192.168.43.1 @192.168.43.1
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NXDOMAIN, id: 50609
;; flags: qr rd ra ad; QUERY: 1, ANSWER: 0, AUTHORITY: 0, ADDITIONAL: 0

;; QUESTION SECTION:
;1.43.168.192.in-addr.arpa.	IN	PTR

;; Query time: 3 msec
;; SERVER: 192.168.43.1#53(192.168.43.1) (UDP)
;; WHEN: Tue Apr 30 11:40:22 IST 2024
;; MSG SIZE  rcvd: 43



```
