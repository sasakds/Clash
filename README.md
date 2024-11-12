# Clash

subconverter后端 Docker安装：
安装命令：


```docker run -d --restart=always -p 25500:25500 tindy2013/subconverter:latest
```


检查命令：（SSH连接openwrt执行命令）


```curl http://localhost:25500/version
```


如果出现 subconverter vx.x.x backend 则说明容器已经成功运行。

如果容器无法启动  重启docker ！
