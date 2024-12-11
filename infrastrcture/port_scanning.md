# Port Scanning

% port scanning
#plateform/linux #target/remote



# Nmap
%Nmap

## tcp basic nmap - syn all ports
```
sudo nmap -v -sS -p- <output_file|nmap/tcp_full_scan> <ip>
```

## tcp nmap common initial scan - syn, versions, all ports, default scripts
```
sudo nmap -v -sS -sV -sC -T4 -p- -oA <output_file|nmap/tcp_full_scan> <ip>
```
