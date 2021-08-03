# termux-nginx-rtmp

## Installation

```sh
apt remove nginx # remove any existing nginx installation.
echo "deb https://muxfd.github.io/termux-nginx-rtmp/ termux extras" > $PREFIX/etc/apt/sources.list.d/nginx-rtmp.list
apt update
apt install nginx-rtmp
```
