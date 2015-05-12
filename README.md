# some-scripts
Some scripts

## install-fis-image-deps.sh

如果安装 FIS 后，如果提供的图片处理库二进制包无法加载使用时，可以执行这个脚本安装这些扩展；

依赖工具

- gcc ( > 4.x)
- cmake
- wget
- git
- node-gyp
- sed / awk / bash

```bash
$ sh ./install-fis-image-deps.sh
```

如果你是用的其他什么解决方案，可以尝试使用如下命令

```bash
$ sh ./install-fis-image-deps.sh fis-plus # install fis-plus
```