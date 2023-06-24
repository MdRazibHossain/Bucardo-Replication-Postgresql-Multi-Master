#   Bucardo-Replication-Postgresql-Multi-Master
Install 2 servers with the base OS being Ubuntu 20.04.

## Master Server 1 : 192.168.122.11
## Master Server 2 : 192.168.122.12

First of all, add the host name in the /etc./hosts both servers (master server 1 and 2)
#### sudo vim /etc/hosts
###### 192.168.122.51 Master1
###### 192.168.122.51	Master2

#### sudo reboot
#### sudo apt update -y
