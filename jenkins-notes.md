# redhat linux OS on virtual box
```
nmcl command to set wifi
```

# virtual box and net connections
```
firstly you need to setup your connection as Ethernet via cable
then you can close session and set your conn as Wifi
restart network adapter via cmd
then you should be connected to your wifi via the same IP address provided by DHCP in first step - ethernet
you dont need to setup wifi ssid or whatever

```

# docker
```
When neither sudo nor apt-get is available in container, you can also jump into running container as root user using command
docker exec -u root -t -i container_id /bin/bash


```
