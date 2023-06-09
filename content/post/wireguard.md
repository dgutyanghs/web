---
# Common-Defined params
title: "wireguard"
date: "2017-08-21"
description: "Example article description"

# Theme-Defined params
#thumbnail: "img/avatar.png" # Thumbnail image
lead: "Example lead - highlighted near the title" # Lead text
comments: false # Enable Disqus comments for specific page
authorbox: false # Enable authorbox for specific page
pager: true # Enable pager navigation (prev/next) for specific page
toc: true # Enable Table of Contents for specific page
mathjax: true # Enable MathJax for specific page
sidebar: "right" # Enable sidebar (on the right side) per page
widgets: # Enable sidebar widgets in given order per page
  - "search"
  - "recent"
  - "taglist"
---

## WireGuard

WireGuard 是一种新的开源 VPN 协议，它有很多优点，例如：

•  易于部署：配置和部署 WireGuard 就像配置和使用 SSH 一样容易，只需要在两端交换公钥，设置防火墙规则并启动服务.

•  高速性能：WireGuard 运行在内核空间，利用了最新的加密技术，可以提供高速且安全的网络连接.

•  低攻击面：WireGuard 有一个仅 4000 行代码的精简代码库，相比 OpenVPN 的 100,000 行代码，更容易调试和审计.

•  IP 无关：WireGuard 使用公钥而不是 IP 端口五元组来标识 Peer，这意味着隧道是 IP 无关的，可以支持地址漫游和动态 IP 变化.

•  对等模式：WireGuard 节点是完全对等的，没有 Server 和 Client 的概念，适合各种组网拓扑.

### 哪些VPN使用了WireGuard

* NordVPN    
* Surfshark  
* StrongVPN  
* IVPN       
* Mullvad    
* VyprVPN     
* OVPN 
* AzireVPN
* VPN.ac
* TorGuard
* Private Internet Access
* CyberGhost

### WireGuard可用来内网穿透
