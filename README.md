# Prerequisites
- [meson](https://mesonbuild.com/)
- [ninja](https://ninja-build.org/)

# Installation
In the following commands `build` is a directory name, feel free to change it.
## Prepare build environment
```bash
meson setup build
```

## Compilation
```bash
cd build
ninja
```

## Automatic tests (optional)
```bash
cd build
ninja test
```

## Install library
```bash
cd build
sudo ninja install
```

## Uninstall library
```bash
cd build
sudo ninja uninstall
```
