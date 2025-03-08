```bash
nmap -vv --reason -Pn -T4 -sU -sV -p 5353 --script="banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/udp_5353_multicastdns_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/xml/udp_5353_multicastdns_nmap.xml" 192.168.43.1
```

[/home/eni9ma/Final/results/192.168.43.1/scans/udp5353/udp_5353_multicastdns_nmap.txt](file:///home/eni9ma/Final/results/192.168.43.1/scans/udp5353/udp_5353_multicastdns_nmap.txt):

```
# Nmap 7.94SVN scan initiated Tue Apr 30 11:48:16 2024 as: nmap -vv --reason -Pn -T4 -sU -sV -p 5353 "--script=banner,(dns* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN /home/eni9ma/Final/results/192.168.43.1/scans/udp5353/udp_5353_multicastdns_nmap.txt -oX /home/eni9ma/Final/results/192.168.43.1/scans/udp5353/xml/udp_5353_multicastdns_nmap.xml 192.168.43.1
Nmap scan report for 192.168.43.1
Host is up, received arp-response (0.017s latency).
Scanned at 2024-04-30 11:48:30 IST for 0s

PORT     STATE SERVICE REASON               VERSION
5353/udp open  mdns    udp-response ttl 255 DNS-based service discovery
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
MAC Address: 0A:2F:E6:1E:43:9D (Unknown)

Host script results:
|_dns-brute: Can't guess domain of "192.168.43.1"; use dns-brute.domain script argument.

Read data files from: /usr/bin/../share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
# Nmap done at Tue Apr 30 11:48:30 2024 -- 1 IP address (1 host up) scanned in 13.71 seconds

```
