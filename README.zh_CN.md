# GXDE Wallpapers

gxde-wallpapers 为 GXDE 桌面环境提供壁纸

## 依赖
请查看“debian/control”文件中提供的“Depends”。

### 编译依赖
请查看“debian/control”文件中提供的“Build-Depends”。

## 安装

### 构建过程

1. 确保已经安装了所有的编译依赖
```bash
sudo apt build-dep gxde-wallpapers
```

2. 构建
```bash
mkdir build
cd build
cmake ..
make
```

3. 安装
```bash
sudo make install
```

## 开源许可证
gxde-wallpapers 在 [GPL-3.0-or-later](LICENSE) 下发布。