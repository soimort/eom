# moe

A fork of the [eom](https://github.com/mate-desktop/eom) image viewer (1.23.0).

## How to build

```
$ ./autogen.sh
$ ./configure \
    --prefix=/usr \
    --localstatedir=/var \
    --with-librsvg
$ make
$ src/eom -n
```
