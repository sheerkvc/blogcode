---
title: Loon的进阶食用(六)→URL Scheme
date: 2/28/2025 21:16
tags: "Loon"
categories: "Loon"
description: loon usage
cover: https://picgo172.oss-cn-qingdao.aliyuncs.com/img/loon.png
highlight_shrink: true #代码框不展开，需点击 '>' 打开
---

> `encode(url)`指你的链接

## URL Scheme

通过URL Scheme可以快速设置Loon的一些选项：

#### 开启VPN

`loon://on`

#### 关闭VPN

`loon://off`

#### 编辑配置文件

`loon://editconfig`

#### 切换流量模式为全局直连

`loon://flowmodel=direct`

#### 切换流量模式为分流

`loon://flowmodel=filter`

#### 切换流量模式为全局代理

`loon://flowmodel=proxy`

#### 设置代理模式为TUN Only

`loon://proxymode=tun`

#### 设置代理模式为HTTP Proxy & TUN

`loon://proxymode=mix`

#### 安装远端配置文件

`loon://import?sub=encode(url)`

#### 导入订阅节点

`loon://import?nodelist=encode(url)`

#### 导入订阅规则

`loon://import?rules=encode(url)`

#### 导入插件

`loon://import?plugin=encode(url)`

#### 导入图标集

`loon://import?iconset=encode(url)`

#### 导入geoip数据库

`loon://import?geoip=encode(url)`

#### 导入解析器

`loon://import?parser=encode(url)`

#### 更新所有订阅资源

`loon://update?sub=all`

------

## 统一链接

统一链接是为了能够在网页中点击链接直接跳转到app中的某个页面，不同链接的作用参考上面的scheme

```loon
- https://www.nsloon.com/openloon/on
- https://www.nsloon.com/openloon/off
- https://www.nsloon.com/openloon/editconfig
- https://www.nsloon.com/openloon/flowmodel=direct
- https://www.nsloon.com/openloon/flowmodel=filter
- https://www.nsloon.com/openloon/flowmodel=proxy
- https://www.nsloon.com/openloon/proxymode=tun
- https://www.nsloon.com/openloon/proxymode=mix
- https://www.nsloon.com/openloon/import?sub=encode(url)
- https://www.nsloon.com/openloon/import?nodelist=encode(url)
- https://www.nsloon.com/openloon/import?rules=encode(url)
- https://www.nsloon.com/openloon/import?plugin=encode(url)
- https://www.nsloon.com/openloon/import?iconset=encode(url)
- https://www.nsloon.com/openloon/import?geoip=encode(url)
- https://www.nsloon.com/openloon/import?parser=encode(url)
- https://www.nsloon.com/openloon/update?sub=all
```

