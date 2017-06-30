# s6-alpine

This is a base Apline image with the [S6 Overlay](https://github.com/just-containers/s6-overlay)

[Alpine Linux](https://alpinelinux.org/) + [S6 Overlay](https://github.com/just-containers/s6-overlay)

## Usage

See the [S6 Overlay Documentation](https://github.com/just-containers/s6-overlay) for details on how to manage services.

x86_64:

```shell
docker run oznu/s6-alpine
```

ARM:

```shell
docker run oznu/s6-alpine:armhf
```
