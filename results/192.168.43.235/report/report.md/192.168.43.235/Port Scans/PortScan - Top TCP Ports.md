```bash
nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.235/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.235/scans/xml/_quick_tcp_nmap.xml" 192.168.43.235
```

[/home/eni9ma/Final/results/192.168.43.235/scans/_quick_tcp_nmap.txt](file:///home/eni9ma/Final/results/192.168.43.235/scans/_quick_tcp_nmap.txt):

```
# Nmap 7.94SVN scan initiated Tue Apr 30 11:39:49 2024 as: nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN /home/eni9ma/Final/results/192.168.43.235/scans/_quick_tcp_nmap.txt -oX /home/eni9ma/Final/results/192.168.43.235/scans/xml/_quick_tcp_nmap.xml 192.168.43.235
Nmap scan report for 192.168.43.235
Host is up, received user-set (0.000053s latency).
Scanned at 2024-04-30 11:40:03 IST for 2s
All 1000 scanned ports on 192.168.43.235 are in ignored states.
Not shown: 1000 closed tcp ports (reset)
Warning: OSScan results may be unreliable because we could not find at least 1 open and 1 closed port
Device type: media device
Running (JUST GUESSING): Microsoft Xbox 360 (85%)
OS CPE: cpe:/h:microsoft:xbox_360_kernel
OS fingerprint not ideal because: Missing an open TCP port so results incomplete
Aggressive OS guesses: Microsoft Xbox 360 Dashboard (85%)
No exact OS matches for host (test conditions non-ideal).
TCP/IP fingerprint:
SCAN(V=7.94SVN%E=4%D=4/30%OT=%CT=1%CU=35789%PV=Y%DS=0%DC=L%G=N%TM=66308B3D%P=x86_64-pc-linux-gnu)
SEQ()
SEQ(CI=Z)
ECN(R=Y%DF=N%TG=40%W=400%O=M5B4%CC=N%Q=)
T1(R=Y%DF=N%TG=40%S=O%A=Z%F=S%RD=0%Q=)
T3(R=Y%DF=N%TG=40%W=400%S=O%A=Z%F=S%O=M5B4%RD=0%Q=)
T5(R=N)
T5(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)
T6(R=N)
T6(R=Y%DF=Y%T=40%W=0%S=A%A=Z%F=R%O=%RD=0%Q=)
T7(R=N)
T7(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)
U1(R=N)
U1(R=Y%DF=N%T=40%IPL=164%UN=0%RIPL=G%RID=G%RIPCK=G%RUCK=G%RUD=G)
IE(R=N)
IE(R=Y%DFI=N%T=40%CD=S)

Network Distance: 0 hops

Read data files from: /usr/bin/../share/nmap
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
# Nmap done at Tue Apr 30 11:40:05 2024 -- 1 IP address (1 host up) scanned in 16.26 seconds

```
