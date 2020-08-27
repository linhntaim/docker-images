# Docker Images

## Build

Command:

```
docker build -f <docker-file> -t gbuatdsquare/<repo-name>[:<tag>] ./
```

- `tag`: For versioning. Can be empty, default: `latest`.

Example:

```
docker build -f uemp.docker -t gbuatdsquare/uemp:latest ./
```

## Run

Command:

```
docker run -it gbuatdsquare/<repo-name>[:<tag>] [<command>]
```

Example:

```
docker run -it gbuatdsquare/uemp:latest bash
```

## Remove

Command:

```
docker image ls
docker image rm <image-id> [--force]
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