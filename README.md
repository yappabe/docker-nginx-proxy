![Docker pulls](https://img.shields.io/docker/pulls/yappabe/nginx-proxy.svg?style=flat)
# Yappa Nginx Proxy Docker Image

## Usage


```
docker run -d  --restart=always -p 80:80 -v /var/run/docker.sock:/tmp/docker.sock:ro yappabe/nginx-proxy
````