- If the apt-get packages are not installing properly, just change to a stable version in `sources.list`

```shell
pi@raspberrypi:~ $ cat /etc/apt/sources.list
#deb https://mirrordirector.raspbian.org/raspbian/ jessie main contrib non-free rpi
# Uncomment line below then 'apt-get update' to enable 'apt-get source'
#deb-src https://archive.raspbian.org/raspbian/ jessie main contrib non-free rpi

deb http://archive.raspbian.org/raspbian wheezy main contrib non-free
deb-src http://archive.raspbian.org/raspbian wheezy main contrib non-free
```
