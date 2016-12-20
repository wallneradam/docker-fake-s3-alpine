# docker-fake-s3-alpine
Minimal fake S3 Docker image based on Alpine linux

It is a minimal Docker image from the [fake-s3](https://github.com/jubos/fake-s3) project.
Uses a persistent volume in /opt/fake-s3/data to store persistence data.

## Usage

```
docker run --rm -d [-p port:port] pickapp/docker-fake-s3 [port]
```

The "port" is 10001 by default.
