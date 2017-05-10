# 一大波·好用的 Atom 插件

### 效果预览

![](http://i.imgur.com/AqWhyGC.png?1)

### 方案 1，下载压缩包替换

1. https://atom.io/ 下载安装 Atom

2. 下载: https://github.com/mdluo/.atom/archive/master.zip

3. 按照下面的路径解压到相应目录，替换原文件

   Windows: `%USERPROFILE%\.atom\`

   Mac/Linux: `~/.atom`

4. 启动 Atom，菜单栏 > Package > Package Sync > Sync Packages

### 方案 2，git 同步

1. 进入路径：

   Windows: `cd %USERPROFILE%\.atom\`

   Mac/Linux: `cd ~/.atom`

2. 命令：

```bash
git init
git remote add origin https://github.com/mdluo/.atom.git
git pull
```

3. 启动 Atom，菜单栏 > Package > Package Sync > Sync Packages
