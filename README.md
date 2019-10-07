# Coder in Docker

## Quick start
```bash
# start coder
docker-compose up -d

# find password
docker-compose logs -f coder

# open coder in browser
# http://localhost:8443/
```

## Environment
```bash
$ cat /etc/redhat-release
CentOS Linux release 7.7.1908 (Core)

$ docker --version
Docker version 1.13.1, build 7f2769b/1.13.1

$ docker-compose --version
docker-compose version 1.24.1, build 4667896b

$ docker images --format "{{.Repository}}:{{.Tag}}"
docker.io/codercom/code-server:1.1156-vsc1.33.1
```
