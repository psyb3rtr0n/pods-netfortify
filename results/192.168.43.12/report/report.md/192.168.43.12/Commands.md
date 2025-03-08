```bash
nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -oN "/home/eni9ma/Final/results/192.168.43.12/scans/_quick_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.12/scans/xml/_quick_tcp_nmap.xml" 192.168.43.12

nmap -vv --reason -Pn -T4 -sV -sC --version-all -A --osscan-guess -p- -oN "/home/eni9ma/Final/results/192.168.43.12/scans/_full_tcp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.12/scans/xml/_full_tcp_nmap.xml" 192.168.43.12

nmap -vv --reason -Pn -T4 -sU -A --top-ports 100 -oN "/home/eni9ma/Final/results/192.168.43.12/scans/_top_100_udp_nmap.txt" -oX "/home/eni9ma/Final/results/192.168.43.12/scans/xml/_top_100_udp_nmap.xml" 192.168.43.12


```