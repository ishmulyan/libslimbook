### Build & Install
```shell
meson setup builddir -Dlibdir=/usr/lib64
meson compile -C builddir
meson install -C builddir