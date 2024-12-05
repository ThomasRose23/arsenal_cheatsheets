# Web App Discovery

# Banner Grab
%Banner Grab

## Banner Grab - Curl
#tags #plateform/linux  #target/remote  #port/  #cat/RECON 

```bash
curl -I <protocol://domain>
```

## Banner Grab - netcat
#tags #plateform/linux  #target/remote  #port/  #cat/RECON 

```bash
netcat -v <domain> <port>
```

# Forced Browsing
% forced browsing

## Hakrawler Forced Browsing
#tags #plateform/linux  #target/remote  #port/  #cat/RECON 

```bash
echo "<domain>" | hakrawler
```

## Dirb Forced Browsing
#tags #plateform/linux  #target/remote  #port/  #cat/RECON 

```bash
dirb <domain>
```

## Dirb Forced Browsing with File Extension
#tags #plateform/linux  #target/remote  #port/  #cat/RECON 

```bash
dirb <domain> -X <extention>
```

# CORS
% cors

## CORS Origin Test with Curl
#tags #plateform/linux  #target/remote  #port/  #cat/RECON 

```bash
curl -X "<method>" -i -H "Origin: <test origin>" -k https://<target>
```
