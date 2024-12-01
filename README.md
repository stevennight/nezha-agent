# Nezha Agent
  
Agent of Nezha Monitoring

## Contributors

<!--GAMFC_DELIMITER--><a href="https://github.com/naiba" title="naiba"><img src="https://avatars.githubusercontent.com/u/29243953?v=4" width="50;" alt="naiba"/></a>
<a href="https://github.com/uubulb" title="UUBulb"><img src="https://avatars.githubusercontent.com/u/35923940?v=4" width="50;" alt="UUBulb"/></a>
<a href="https://github.com/funnyzak" title="Leon"><img src="https://avatars.githubusercontent.com/u/2562087?v=4" width="50;" alt="Leon"/></a>
<a href="https://github.com/zhangnew" title="zhangnew"><img src="https://avatars.githubusercontent.com/u/9146834?v=4" width="50;" alt="zhangnew"/></a>
<a href="https://github.com/AEnjoy" title="AEnjoy"><img src="https://avatars.githubusercontent.com/u/37976919?v=4" width="50;" alt="AEnjoy"/></a>
<a href="https://github.com/wwng2333" title=":D"><img src="https://avatars.githubusercontent.com/u/17147265?v=4" width="50;" alt=":D"/></a>
<a href="https://github.com/DarcJC" title="Darc Z."><img src="https://avatars.githubusercontent.com/u/53445798?v=4" width="50;" alt="Darc Z."/></a>
<a href="https://github.com/xykt" title="xykt"><img src="https://avatars.githubusercontent.com/u/152045469?v=4" width="50;" alt="xykt"/></a>
<a href="https://github.com/Erope" title="卖女孩的小火柴"><img src="https://avatars.githubusercontent.com/u/44471469?v=4" width="50;" alt="卖女孩的小火柴"/></a>
<a href="https://github.com/liuran001" title="Chisato22"><img src="https://avatars.githubusercontent.com/u/32791471?v=4" width="50;" alt="Chisato22"/></a><!--GAMFC_DELIMITER_END-->


# Actions编译
通过github actions进行构建。

## 触发构建

```bash
# 替换版本号
git tag vx.x.x
git push --tags
```

## 完成构建
构建完成后，仓库的release会有最新的版本。

# Go 编译

## 安装Go Releaser
https://goreleaser.com/install/

## 安装编译环境（ubuntu, debian系）
```bash
sudo apt-get install gcc-s390x-linux-gnu
sudo apt-get install gcc-aarch64-linux-gnu
sudo apt-get install mingw-w64
```

## 编译
```bash
goreleaser release
```