# certsforUnblockNeteaseMusic
certs for UnblockNeteaseMusic v0.25.3

从 nondanee 大佬这里下新的证书https://github.com/nondanee/UnblockNeteaseMusic/releases/tag/v0.25.3

然后进入你的路由器，
nodejs 版本证书存放路径: /usr/share/UnblockNeteaseMusic
go 版本的证书存放路径: /usr/share/UnblockNeteaseMusicGo

替换三个文件即可:
ca.crt
server.crt
server.key


IOS 客户端
首先下载安装 ca.cert, 并在通用里信任证书

再进行设置
1.网络设置，找到连入的 wifi
2.进入参数设置，找到 HTTP PROXY
3.进入 Configure Proxy，选择 Automatic，URL 留空
4.保存
5.打开网易云 app，搜索“周杰伦”进行测试，歌曲正常并能正常播放，完成 IOS 端设置
