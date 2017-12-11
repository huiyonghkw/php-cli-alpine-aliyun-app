#  PHP 7 CLI basic docker images  based on Alpine

This image based entirely on alpine Linux, installing PHP extensions and 7 CLI mode.In addition, use the [Ali - OSM Alibaba, the Open Source](http://mirrors.aliyun.com/) Mirror Site services to accelerate the domestic access.


此镜像完全基于alpine linux，安装PHP 7 扩展和CLI模式。另外，使用了 [Ali-OSM - Alibaba Open Source Mirror Site ](http://mirrors.aliyun.com/ )服务加速中国内地访问速度

## Upgrade


`2017-12-11` [413 request entity too large](https://www.iteblog.com/archives/1421.html)

`2017-12-04` Support [PHP7 extension for interfacing with memcached via libmemcached library](https://pkgs.alpinelinux.org/package/edge/community/x86/php7-memcached)

`2017-11-06` Support [PHP7 extension for ZeroMQ](https://pkgs.alpinelinux.org/package/edge/community/x86/php7-zmq), The ZeroMQ messaging library and tools.


## Build & Push

1. Docker build image
```bash
❯ docker build -t bravist/php-cli-alpine-aliyun-app:1.10 .
```

2. Login [Docker Hub](https://hub.docker.com)
```bash
❯ docker login
Username (bravist):
Password:
Login Succeeded
```

3. Push image to [Docker Hub](https://hub.docker.com)
```bash
❯ docker push bravist/php-cli-alpine-aliyun-app:1.10
```

