[![Docker Stars](https://img.shields.io/docker/stars/mielune/alpine-python3-arm.svg?style=flat-square)](https://hub.docker.com/r/mielune/alpine-python3-arm/)
[![Docker Pulls](https://img.shields.io/docker/pulls/mielune/alpine-python3.svg?style=flat-square)](https://hub.docker.com/r/mielune/alpine-python3-arm/)


Python 3 Docker image for ARM arch
=======================

This image is based on Alpine Linux image build by Hypriot for Raspberry Pi, which is only a 6.7MB image,
The latest release is based on the stable 3.5 Alpine packages and contains [Python 3.5.2](https://www.python.org).
The edge release is based on the 'edge' Alpine packages and contains [Python 3.6.1](https://www.python.org).

Download size of this image is only:

Python 3.5 [![](https://images.microbadger.com/badges/image/mielune/alpine-python3-arm.svg)](https://microbadger.com/images/mielune/alpine-python3-arm "Get your own image badge on microbadger.com")
Python 3.6 [![](https://images.microbadger.com/badges/image/mielune/alpine-python3-arm:edge.svg)](https://microbadger.com/images/mielune/alpine-python3-arm:edge "Get your own image badge on microbadger.com")

Usage
-------------

Example for Python 3.5 (latest/stable release of Alpine)
=============

```bash
$ docker run --rm mielune/alpine-python3-arm python3 -c 'print("Hello World")'
```

Example for Python 3.6 (edge/unstable release of Alpine)
=============

```bash
$ docker run --rm mielune/alpine-python3-arm:edge python3 -c 'print("Hello World")'
```

Once you have run this command you will get printed 'Hello World' from Python!

NOTE: `pip`/`pip3` is also available in this image.

Thank's to [Hypriot](https://github.com/hypriot) for the Raspberry build of Alpinelinux and to [frolvlad](https://hub.docker.com/u/frolvlad/) for the Alpine-Python3 project from where I forked.

