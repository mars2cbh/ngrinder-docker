# nGrinder Docker Compose

## nGrinder github page
- [https://github.com/naver/ngrinder](https://github.com/naver/ngrinder)

## Controller

```
$ docker-compose -f controller-docker-compose.yml up
```
Connect to admin page - IP:8880   
Administrator Account   
+ ID / PW : admin / admin

## Agent

edit agent-docker-compose.yml

```
__CONTROLLER_IP__ -> controller ip address
```
```
$ docker-compose -f agent-docker-compose.yml up
```

