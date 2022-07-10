# Dock

Piscesys application dock.

## Dependencies (For Arch)

```shell
sudo pacman -S gcc cmake qt5-base qt5-quickcontrols2 kwindowsystem
```

You also need [`fishui`](https://github.com/piscesys/fishui) and [`libpisces`](https://github.com/piscesys/libpisces).

## Build and Install

```
git clone https://github.com/cirily/dock.git
cd dock
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

## License

This project has been licensed by GPLv3.
