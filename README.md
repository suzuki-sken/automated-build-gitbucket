# docker-gitbucket

docker image for gitbucket-2.6 with java-1.7.0-openjdk on centos.

## Usage

```
coreos$ sudo mkdir -p /opt/data/gitbucket
coreos$ docker run -d -p 8080:8080 -v /opt/data/gitbucket:/gitbucket sken/gitbucket
```
