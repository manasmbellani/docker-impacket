# Docker impacket container

## Install
```
docker build . -t impacket
```

## Example 
```
docker run -it --rm impacket GetUserSPNs.py -request MYAD.LAN/test

docker run -it --rm impacket secretsdump.py -just-dc-ntlm <domain>/Administrator:<password>@<dc-ip>
```
