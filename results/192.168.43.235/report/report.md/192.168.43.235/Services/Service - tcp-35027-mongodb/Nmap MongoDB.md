```bash
nmap -vv --reason -Pn -T4 -sV -p 35027 --script="banner,(mongodb* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN "/home/eni9ma/Final/results/192.168.43.235/scans/tcp35027/tcp_35027_mongodb_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.235/scans/tcp35027/xml/tcp_35027_mongodb_nmap.xml" 192.168.43.235
```

[/home/eni9ma/Final/results/192.168.43.235/scans/tcp35027/tcp_35027_mongodb_nmap.txt](file:///home/eni9ma/Final/results/192.168.43.235/scans/tcp35027/tcp_35027_mongodb_nmap.txt):

```
# Nmap 7.94SVN scan initiated Tue Apr 30 02:01:14 2024 as: nmap -vv --reason -Pn -T4 -sV -p 35027 "--script=banner,(mongodb* or ssl*) and not (brute or broadcast or dos or external or fuzzer)" -oN /home/eni9ma/Final/results/192.168.43.235/scans/tcp35027/tcp_35027_mongodb_nmap.txt -oX /home/eni9ma/Final/results/192.168.43.235/scans/tcp35027/xml/tcp_35027_mongodb_nmap.xml 192.168.43.235
Nmap scan report for 192.168.43.235
Host is up, received user-set (0.000042s latency).
Scanned at 2024-04-30 02:01:14 IST for 0s

PORT      STATE SERVICE REASON         VERSION
35027/tcp open  unknown syn-ack ttl 64
| fingerprint-strings: 
|   NULL: 
|_    {"type":"Tier1","version":"1.0"}
|_banner: {"type":"Tier1","version":"1.0"}
1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at https://nmap.org/cgi-bin/submit.cgi?new-service :
SF-Port35027-TCP:V=7.94SVN%I=7%D=4/30%Time=66300392%P=x86_64-pc-linux-gnu%
SF:r(NULL,22,"{\"type\":\"Tier1\",\"version\":\"1\.0\"}\r\n");

Read data files from: /usr/bin/../share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
# Nmap done at Tue Apr 30 02:01:14 2024 -- 1 IP address (1 host up) scanned in 0.50 seconds

```
