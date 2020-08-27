# Docker Images

## Build

Command:

```
docker build -f <docker-file> -t gbuatdsquare/<repo-name>[:<tag>] ./
```

- `tag`: For versioning. Can be empty, default: `latest`.

Example:

```
docker build -f uemp.docker -t gbuatdsquare/uemp:lastest ./
```

## Push

Command:

```
docker push gbuatdsquare/<repo-name>[:<tag>]
```

- `tag`: For versioning. Can be empty, default: `latest`.

Example:

```
docker push gbuatdsquare/uemp:latest
```