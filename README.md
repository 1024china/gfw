# 客户端
#####  推荐小白使用：大杀器,支持多客户端(需要先翻, 才能正常访问大杀器网址)
> 官网 https://gfw.press/
> 使用帮助 https://gfw.press/blog/?p=2047
#####  Shadowsocks 客户端及 APP 下载
> Windows 电脑客户端下载
- [Shadowsocks 国内 CDN 高速下载 ](https://dn-shimo-attachment.qbox.me/b0Um2Js1mBoqeMV4%2FSYJBKZRgt0oRGs7K?attname=SS-Win.zip "Shadowsocks 国内 CDN 高速下载 ")
[Shadowsocks 国内备份下载](https://www.babel.cc/share.do?s=7966045981310736 "Shadowsocks 国内备份下载")

> 安卓客户端下载
- [shadowsocks 影梭国内 CDN 高速下载](https://dn-shimo-attachment.qbox.me/b0Um2Js1mBoqeMV4%2FAVAAymgzYrglH5XB?attname=shadowsocks-nightly-4.1.8.apk "hadowsocks 影梭国内 CDN 高速下载")
- [ 国内备份下载](https://www.babel.cc/share.do?s=7105933012929395 " 国内备份下载")

> Mac 苹果客户端下载
- [ShadowsocksX-NG-SSR 国内 CDN 高速下载](https://dn-shimo-attachment.qbox.me/b0Um2Js1mBoqeMV4%2Flaw3fwzlSi8JliNq?attname=ShadowsocksX-NG-R8.dmg "ShadowsocksX-NG-SSR 国内 CDN 高速下载")
- [ShadowsocksX-NG-SSR 国内备份下载](https://www.babel.cc/share.do?s=1540367796358713 "ShadowsocksX-NG-SSR 国内备份下载")

>ios 客户端下载
-  [SsrConnect下载](https://itunes.apple.com/nl/app/shadowconnect/id1161221960?mt=8&uo=4&at=1010lpjB&ct=tas "SsrConnect")     
 [SsrConnect使用教程](https://lai.yuweining.cn/archives/246/ "使用教程")
- [ AnyFlow Lite下载](https://itunes.apple.com/cn/app/anyflow-lite/id1195285629?mt=8 " AnyFlow Lite")
[ AnyFlow Lite使用教程](https://lai.yuweining.cn/archives/788/ "使用教程")
- [-IOS 下的影梭 Shadowsocks APP 汇总](https://lai.yuweining.cn/archives/159/ "-IOS 下的影梭 Shadowsocks APP 汇总")
------------
# 配置
##### 免费服务器配置1           [lai.yuweining.cn](http://yuweining.cn/leifeng/ "lai.yuweining.cn")提供
| 服务器/ip地址  | ss1.ubox.co<br>ss6.ubox.co   |
| :------------: | :------------: |
| 端口   | 8388  |
| 密码  |  password |
|加密方式   | aes-256-cfb  |


#####   免费服务器配置2       ([lai.yuweining.cn](http://yuweining.cn/leifeng/ "lai.yuweining.cn") 提供 不限流量 长期可用 兼容SS 与 SSR)
|         | |                             |
| ------------ | --- | ------------------------------- |
| 服务器/ip地址 |  leifeng1.yuweining.cn<br>leifeng2.yuweining.cn<br>leifeng3.yuweining.cn<br>leifeng4.yuweining.cn
| 端口   |  888 |        |
| 密码| yuweining.cn （密码手动输入，复制容易出错。）|
| 加密方式| chacha20|
| 协议| auth_sha1_v4 |
| 混淆|tls1.2_ticket_auth|

------------
# 其他免费ss账号
https://shadowsocksr.ru/    <br>
https://twitter.com/yuricloner <br>
https://github.com/Alvin9999/new-pac/wiki/ss%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7  <br>
https://get.freevpnss.me/#shadowsocks <br>

------------
# 技术科普

 ##### shadowsocks使用说明-手机版-电脑板-ISO版-安卓版
 
http://www.o0o0o.ml/?p=96

#####  GFW翻墙小结
https://wsgzao.github.io/post/fq/

##### VPS

http://www.asiaserverhost.com/

##### Shadowsocks安装一键脚本

wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log

编辑配置文件 用VI编辑器 方法请谷歌
vi /etc/shadowsocks-python/config.json

Shadowsocks常用命令

/etc/init.d/shadowsocks-python start | stop | restart | status

Shadowsocks重启命令

/etc/init.d/shadowsocks-python restart

检测连接数 需要安装netstat请谷歌
netstat -an | grep 17863 | grep ESTABLISHED | wc -l
netstat -an | grep 52113 | grep ESTABLISHED | wc -l

BBR安装一键脚本，仅限搬瓦工Openvz架构，记住是Openvz架构，不是Kvm架构，就是那个2000GB的那个才适用
其他请谷歌

wget https://raw.githubusercontent.com/kuoruan/shell-scripts/master/ovz-bbr/ovz-bbr-installer.sh
chmod +x ovz-bbr-installer.sh
./ovz-bbr-installer.sh


 
