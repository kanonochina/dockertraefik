# Docker container management with Traefik v2 and Portainer


## How to run it?

```
$ git clone https://github.com/kanonochina/dockertraefik.git ./src
$ cd src/core
$ docker network create proxy
```

## Add username password to traefik-data/configuration

```  
$ echo $(htpasswd -nb <username> <password>)

$ docker-compose up -d
```
Reference [Traefik plus Docker](https://rafrasenberg.com/posts/docker-container-management-with-traefik-v2-and-portainer/)