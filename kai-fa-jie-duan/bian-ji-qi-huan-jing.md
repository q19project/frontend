# 编辑器环境

## 1. 安装vscode

{% embed url="https://code.visualstudio.com/" %}

不用下载Insider版本，最新版vscode已经支持Remote Development

## 2. 配置ssh服务

```text
vim ~/.ssh/config
```

新增云服务配置

```text
Host 云主机名称
  HostName 云主机ip地址
  Port 云主机ssh服务开放端口
  User 云主机默认登录用户
```

> 如果服务器上git版本过低\(低于2.0\)，可以手动下载git源码包\(tar.gz格式\)进行编译安装。



