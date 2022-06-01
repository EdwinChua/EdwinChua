# Notes for docker images

## MySQL image

Starts a container
- Loaded with MySQL (tag 8)
- Sets the default password
- Sets the default TCP port
- Maps the TCP port to a port on the host

```cmd
docker run --name mysql_1 -e MYSQL_ROOT_PASSWORD=123456 -e MYSQL_TCP_PORT=3307 -p 3307:3307 -d mysql:8
```


## Redis

https://redis.com/blog/get-redis-cli-without-installing-redis-server/
