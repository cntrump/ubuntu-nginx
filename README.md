# Nginx on Ubuntu Docker image

Base on Ubuntu 20.04

Nginx version 1.18.0, build with clang 10.


## Docker Image

```shell
docker pull cntrump/ubuntu-nginx:latest
```

Run Nginx

```shell
docker run -it --rm -p 80:80 -p 443:443 cntrump/ubuntu-nginx:latest
```
