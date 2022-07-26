# Nginx Simple DockerFile Readme

## Build

进入Dockerfile目录，执行：

```shell
docker build -t nginx/test:v1 .
```

如需对Nginx配置文件进行修改，请执行

```shell

```

## run

```shell
docker run --name nginx-test -d -p 8080:80 nginx/test:v1
```
