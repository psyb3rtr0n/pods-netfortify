```bash
nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml" 192.168.43.1
```

[/home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt](file:///home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt):

```
# Nmap 7.94SVN scan initiated Tue Apr 30 11:39:49 2024 as: nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN /home/eni9ma/Final/results/192.168.43.1/scans/_full_tcp_nmap.txt -oX /home/eni9ma/Final/results/192.168.43.1/scans/xml/_full_tcp_nmap.xml 192.168.43.1
Nmap scan report for 192.168.43.1
Host is up, received arp-response (0.0032s latency).
Scanned at 2024-04-30 11:40:03 IST for 35s
Not shown: 65534 closed tcp ports (reset)
PORT   STATE SERVICE REASON         VERSION
53/tcp open  domain  syn-ack ttl 64 dnsmasq 2.51
| dns-nsid: 
|_  bind.version: dnsmasq-2.51
MAC Address: 0A:2F:E6:1E:43:9D (Unknown)
Aggressive OS guesses: Linux 2.6.32 (96%), Linux 3.2 - 4.9 (96%), Linux 2.6.32 - 3.10 (96%), Android 4.1 - 6.0 (Linux 3.4 - 3.14) (96%), Android 5.0 - 6.0.1 (Linux 3.4) (96%), Android 5.0 - 7.0 (Linux 3.4 - 3.10) (96%), Android 4.2.2 (Linux 3.4) (95%), Linux 3.2 - 3.16 (95%), Linux 3.1 (95%), Linux 3.2 (95%)
No exact OS matches for host (If you know what OS is running on it, see https://nmap.org/submit/ ).
TCP/IP fingerprint:
OS:SCAN(V=7.94SVN%E=4%D=4/30%OT=53%CT=1%CU=36375%PV=Y%DS=1%DC=D%G=Y%M=0A2FE
OS:6%TM=66308B5E%P=x86_64-pc-linux-gnu)SEQ(SP=104%GCD=1%ISR=10C%TI=Z%CI=Z%I
OS:I=I%TS=7)OPS(O1=M5B4ST11NW9%O2=M5B4ST11NW9%O3=M5B4NNT11NW9%O4=M5B4ST11NW
OS:9%O5=M5B4ST11NW9%O6=M5B4ST11)WIN(W1=FFFF%W2=FFFF%W3=FFFF%W4=FFFF%W5=FFFF
OS:%W6=FFFF)ECN(R=Y%DF=Y%T=40%W=FFFF%O=M5B4NNSNW9%CC=Y%Q=)T1(R=Y%DF=Y%T=40%
OS:S=O%A=S+%F=AS%RD=0%Q=)T2(R=N)T3(R=N)T4(R=Y%DF=Y%T=40%W=0%S=A%A=Z%F=R%O=%
OS:RD=0%Q=)T5(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)T6(R=Y%DF=Y%T=40%W
OS:=0%S=A%A=Z%F=R%O=%RD=0%Q=)T7(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)
OS:U1(R=Y%DF=N%T=40%IPL=164%UN=0%RIPL=G%RID=G%RIPCK=G%RUCK=G%RUD=G)IE(R=Y%D
OS:FI=N%T=40%CD=S)

Uptime guess: 0.269 days (since Tue Apr 30 05:13:17 2024)
Network Distance: 1 hop
TCP Sequence Prediction: Difficulty=260 (Good luck!)
IP ID Sequence Generation: All zeros

TRACEROUTE
HOP RTT     ADDRESS
1   3.15 ms 192.168.43.1

Read data files from: /usr/bin/../share/nmap
OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
# Nmap done at Tue Apr 30 11:40:38 2024 -- 1 IP address (1 host up) scanned in 49.54 seconds

```
