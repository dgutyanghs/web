---
title: "Openwrt开源镜像安全性的思考"
date: 2023-06-10T15:25:25+08:00
draft: true
---

# Openwrt 科学上网镜像的思考
##  网友LEAN开源的源码仓库
编译方法按github提供即可[点击访问](https://github.com/coolsnowwolf/lede)。
需要注意的是它源码不带科学上网工具，如passwall, Helloworld, openclash等，需要你手动下载。工具地址[点击访问](https://github.com/kenzok8/openwrt-packages)

优点：开源透明，自由选择性高。
缺点：编译过程对一般人来说，有一定的难度。


## KoolCenter团队的源码仓库
即原来的KoolShare团队，在ASUS-Merlin上开发出Koolshare版本，但拒绝遵守GPL协议，不开源。
istoreOS[点击访问](https://github.com/istoreos)属于易有云网络科技有限责任公司运营的项目，以提供openwrt软件中心iStore为推广点，插件下载升级方便。
软件中心在提供给你的方便同时，安全性存疑。


优点：istoreOS 本身开源，有软件中心，方便日后升级，加装新插件等。
缺点：软件中心安装的插件不能保证其安全性，由于是公司运营，受政府相关法规管控。


## 总结
针对上述列举，本人推荐你自己编译源码，如果觉得太难，请根据自己的硬件设备在github搜索一下其它大V已经编译号的镜像。（源码必须开源）

关于我KoolCenter团队的istoreOS的插件可能产生的安全问题，纯属本人臆测，并无证据，读者自行判断，为避免争议，特此声明。

