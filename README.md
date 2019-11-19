# Alpine image with `git` `build-base` and `linux-headers`

## Overview
Build image for multi-part build

- Build
```shell
docker build -t hello/go-alpine-build .
```

- Run
```shell
docker run -it hello/go-alpine-build
```

- Push
```shell
docker push hello/go-alpine-build
```