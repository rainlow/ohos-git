# ohos-git
本项目为 OpenHarmony 平台编译了 git，并发布预构建包。

## 获取预构建包
前往 [release 页面](https://github.com/Harmonybrew/ohos-git/releases) 获取。

## 从源码构建
需要用一台 Linux x64 服务器来运行项目里的 build.sh，以实现 git 的交叉编译。

这里以 Ubuntu 24.04 x64 作为示例：
```sh
sudo apt update && sudo apt install -y build-essential autoconf gettext file unzip jq
./build.sh
```
