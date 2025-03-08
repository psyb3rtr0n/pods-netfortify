```bash
nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml" 192.168.43.1
```

[/home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt](file:///home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt):

```
# Nmap 7.94SVN scan initiated Tue Apr 30 11:39:49 2024 as: nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN /home/eni9ma/Final/results/192.168.43.1/scans/_top_100_udp_nmap.txt -oX /home/eni9ma/Final/results/192.168.43.1/scans/xml/_top_100_udp_nmap.xml 192.168.43.1
Nmap scan report for 192.168.43.1
Host is up, received arp-response (0.0026s latency).
Scanned at 2024-04-30 11:40:03 IST for 493s
Not shown: 82 open|filtered udp ports (no-response)
PORT      STATE  SERVICE      REASON               VERSION
9/udp     closed discard      port-unreach ttl 64
53/udp    open   domain       udp-response ttl 64  dnsmasq 2.51
| dns-nsid: 
|_  bind.version: dnsmasq-2.51
|_dns-recursion: Recursion appears to be enabled
161/udp   closed snmp         port-unreach ttl 64
497/udp   closed retrospect   port-unreach ttl 64
997/udp   closed maitrd       port-unreach ttl 64
1022/udp  closed exp2         port-unreach ttl 64
1023/udp  closed unknown      port-unreach ttl 64
1025/udp  closed blackjack    port-unreach ttl 64
1026/udp  closed win-rpc      port-unreach ttl 64
1030/udp  closed iad1         port-unreach ttl 64
1433/udp  closed ms-sql-s     port-unreach ttl 64
1718/udp  closed h225gatedisc port-unreach ttl 64
2048/udp  closed dls-monitor  port-unreach ttl 64
5060/udp  closed sip          port-unreach ttl 64
5353/udp  open   mdns         udp-response ttl 255 DNS-based service discovery
| dns-service-discovery: 
|   56666/udp mi-connect
|     idHash=MTY2
|     dev=1
|     sec=2
|     apps=[8193, 8194]
|     name=Doomz Day
|     flags=Ag==
|     version=65540
|     commonData=0
|     appsData=AwIEgwIEgw==
|_    Address=192.168.43.1 2409:4080:e19:3107::9b
17185/udp closed wdbrpc       port-unreach ttl 64
33281/udp closed unknown      port-unreach ttl 64
49181/udp closed unknown      port-unreach ttl 64
MAC Address: 0A:2F:E6:1E:43:9D (Unknown)
Too many fingerprints match this host to give specific OS details
TCP/IP fingerprint:
SCAN(V=7.94SVN%E=4%D=4/30%OT=%CT=%CU=9%PV=Y%DS=1%DC=D%G=N%M=0A2FE6%TM=66308D28%P=x86_64-pc-linux-gnu)
SEQ(CI=Z%II=I)
T5(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)
T6(R=Y%DF=Y%T=40%W=0%S=A%A=Z%F=R%O=%RD=0%Q=)
T7(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)
U1(R=Y%DF=N%T=40%IPL=164%UN=0%RIPL=G%RID=G%RIPCK=G%RUCK=G%RUD=G)
IE(R=Y%DFI=N%T=40%CD=S)

Network Distance: 1 hop

TRACEROUTE
HOP RTT     ADDRESS
1   2.61 ms 192.168.43.1

Read data files from: /usr/bin/../share/nmap
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
# Nmap done at Tue Apr 30 11:48:16 2024 -- 1 IP address (1 host up) scanned in 507.02 seconds

```
