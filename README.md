# 图床

#### 介绍
配合picgo使用的私人图床

#### 安装教程

1.  下载 `picgo` https://github.com/Molunerfinn/PicGo
2.  配置 `picgo` 的 `github` 图床
  - 仓库名: `coolmoon327/picBed`
  - 分支名: `master`
  - Token: Github 生成（Settings-Developer Settings-Tokens-Classic-勾选 repo）
3.  设置“时间戳重命名”

#### Debug

- macOS 无法打开文件：

```
sudo xattr -d com.apple.quarantine "/Applications/PicGo.app"
```
