
```shell script
docker build admin-server
```

```shell script
docker run --rm -it -p "localhost:8080:8080" org.radug.springbits/admin-server
```

```shell script
docker build org.radug.springbits/admin-client
```

```shell script
docker run --rm -it org.radug.springbits/admin-client
```

```shell script
docker stack deploy --compose-file docker-compose.yml springswarm
```