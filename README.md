# GXDE Wallpapers

gxde-wallpapers provides wallpapers of GXDE Desktop

## Dependencies
You can also check the "Depends" provided in the `debian/control` file.

### Build dependencies
You can also check the "Build-Depends" provided in the `debian/control` file.

## Installation

### Build from source code

1. Make sure you have installed all dependencies.
```bash
sudo apt build-dep gxde-wallpapers
```

2. Build
```bash
mkdir build
cd build
cmake ..
make
```

3. Install
```bash
sudo make install
```

## License
gxde-wallpapers is licensed under [GPL-3.0-or-later](LICENSE).
