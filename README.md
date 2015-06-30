# Samba for Raspberry Pi 2

This is a Dockerfile to set up [Samba](https://samba.org/).

This container will share a *public* folder with the attached `data` container.

# Usage

```shell
$ docker run \
  -p 137:137
  -p 138:138
  -p 139:139
  -p 445:455
  -v /mnt/data:/data
  nunofgs/rpi-samba
```
