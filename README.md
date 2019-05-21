[![Docker Stars](https://img.shields.io/docker/stars/neteler/docker-alpine-grass-gis.svg?style=flat-square)](https://hub.docker.com/r/neteler/docker-alpine-grass-gis/)
[![Docker Pulls](https://img.shields.io/docker/pulls/neteler/docker-alpine-grass-gis.svg?style=flat-square)](https://hub.docker.com/r/neteler/docker-alpine-grass-gis/)
[![License](https://img.shields.io/github/license/neteler/docker-alpine-grass-gis.svg?style=flat-square)](https://www.apache.org/licenses/LICENSE-2.0)


# Docker GRASS GIS (alpine linux)

Credits to https://github.com/zarch/docker-alpine-grass-gis

Dockerfile with an [Alpine Linux](https://www.alpinelinux.org/) image with [GRASS GIS](https://grass.osgeo.org/) and [grass-session](https://github.com/zarch/grass-session/).

Download size of this image is only:

[![](https://images.microbadger.com/badges/image/zarch/alpine-grass-gis.svg)](https://microbadger.com/images/zarch/alpine-grass-gis "Get your own image badge on microbadger.com")



Build the docker with:

```bash
$ sudo docker build --build-arg GRASS_VERSION=7.7 \
                    --build-arg PYTHON_VERSION=3  \
                    --build-arg PROJ_VERSION=5.2.0 \
                    --build-arg PROJ_DATUMGRID_VERSION=1.8 \
                    .
```

View the images available using `sudo docker images` and open a bash terminal with:

```bash
$ sudo docker run -i -t 15550df91610 /bin/bash
bash-5.0#
```
