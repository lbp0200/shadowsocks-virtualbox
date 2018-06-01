# shadowsocks-virtualbox
将shadowsock打包进虚拟机，开箱即用，免去部署烦恼。

内置ss免费节点账号。

# 安装
1. 安装VirtualBox
2. 在本项目Release中，下载ss.ova。百度盘镜像链接: https://pan.baidu.com/s/1MgX2xx2I0Y4bSuYC6uACUw 密码: yjm4
3. 打开VirtualBox，导入ss.ova，启动导入的虚拟机。
4. 打开浏览器，如Firefox，设置网络代理为`socks5 127.0.0.1:1080`或`HTTP 127.0.0.1:8123`，开始科学上网。

# 设置
虚拟机中，shadowsocks监听1080，http代理监听8123，可以随时在`网络`-`端口转发`中，设置虚拟机映射到母机的端口。

# 为什么里面的设置不开源？
因为设置是见光死的东西，很快就会被封，低调使用。

# 如何分享给身边的人？
低调使用，不要写博客分享，吸引眼球。分享给身边的人时，不要使用QQ、微信等被实时监控的通讯工具，也许email分享是个目前可行的方案。

# 速度好像不快？
节点对电信、移动友好，联通不太好。

有条件还是推荐自己搭建，根据本人经历，年付的VPS一般比较坑，可能是人满为患的原因。`ping`值不是很重要，不丢包就好。

推荐新手用[搬瓦工](https://polr.liuboping.com/9zuU9)

进阶使用[Vultr](https://polr.liuboping.com/PrgTf)

# 遇到问题，如何解决？
重启虚拟机能解决大部分问题
