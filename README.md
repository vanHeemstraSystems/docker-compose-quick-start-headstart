docker-compose-quick-start-headstart
# Docker Compose Quick Start - Head Start

Based on "Install Docker Compose" at https://docs.docker.com/compose/install/

For Linux (using a server of Linux Academy):

```
69e2a4cfec1c login: cloud_user
Password: 
[cloud_user@69e2a4cfec1c ~]$ docker-compose version
-bash: docker-compose: command not found
[cloud_user@69e2a4cfec1c ~]$ docker-compose --version
-bash: docker-compose: command not found
[cloud_user@69e2a4cfec1c ~]$ sudo curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
[sudo] password for cloud_user: 
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   633  100   633    0     0   1645      0 --:--:-- --:--:-- --:--:--  1652
100 11.6M  100 11.6M    0     0  14.9M      0 --:--:-- --:--:-- --:--:-- 41.1M
[cloud_user@69e2a4cfec1c ~]$ docker-compose --version
-bash: /usr/local/bin/docker-compose: Permission denied
[cloud_user@69e2a4cfec1c ~]$ sudo chmod +x /usr/local/bin/docker-compose
[cloud_user@69e2a4cfec1c ~]$ docker-compose --version
docker-compose version 1.28.2, build 67630359
[cloud_user@69e2a4cfec1c ~]$ 
```
