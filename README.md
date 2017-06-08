ubuntu armhf base image with qemu, enable capability build armhf image on x86 and docker hub

### FROM

https://github.com/resin-io-projects/armv7hf-debian-qemu

https://resin.io/blog/building-arm-containers-on-any-x86-machine-even-dockerhub/

[armhf/ubuntu](https://hub.docker.com/r/armhf/ubuntu/)

[arm32v7/ubuntu](https://hub.docker.com/r/arm32v7/ubuntu/)

### TAGS

17.10, artful

14.04, trusty

16.04, xenial, latest

16.10, yakkety

17.04, zesty

### RUN

RUN [ "cross-build-start" ]

...

RUN [ "cross-build-end" ]
