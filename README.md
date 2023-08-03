# Wechat-Electron

wechat-electron 是一个用 Electron 和微信网页版构建的微信桌面客户端。
它具有所有微信的功能，包括聊天、发送文件、发送表情包等。


## 下载安装

### Ubuntu
1. 打开终端窗口
2. 使用`wget`命令下载打包文件
```
wget https://github.com/ChanMo/wechat-electron/raw/main/out/make/deb/x64/wechat_1.0.0_amd64.deb?download=
```
3. 使用`dpkg`命令安装打包文件
```
sudo dpkg -i wechat_1.0.0_amd64.deb
```

### CentOS
1. 打开终端窗口
2. 使用`wget`命令下载打包文件
```
wget https://github.com/ChanMo/wechat-electron/raw/main/out/make/rpm/x64/wechat-1.0.0-1.x86_64.rpm?download=
```
3. 使用`yum`命令安装打包文件
```
sudo yum install wechat-1.0.0-1.x86_64.rpm
```


## 许可证
MIT

## 更新日志

* 2023-03-08
    * 初始版本发布
