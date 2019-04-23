# Awesome Go
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


- 实用库
	- [denisbrodbeck/machineid](<https://github.com/denisbrodbeck/machineid>) 获得唯一的机器识别码(不需要管理员权限)
	- [blevesearch/bleve](<https://github.com/blevesearch/bleve>) 现代文本索引/检索库
	- [tealeg/xlsx](<https://github.com/tealeg/xlsx>) 处理Excel(.xlsx)
	- [360EntSecGroup-Skylar/excelize](<https://github.com/360EntSecGroup-Skylar/excelize>) 处理Excel(.xlsx)
	- [chrislusf/glow](<https://github.com/chrislusf/glow>) 分布式计算系统
	- [panjf2000/ants](<https://github.com/panjf2000/ants>) 高性能的协程池
	- [Jeffail/tunny](<https://github.com/Jeffail/tunny>) 也是一个协程池
	- [gliderlabs/ssh](<https://github.com/gliderlabs/ssh>) 可以用Golang实现SSH Server (支持scp,端口转发等)
	- [abiosoft/ishell](<https://github.com/abiosoft/ishell>) 用于开发交互式CLI程序的库
- 实用工具
	
	- [motemen/gore](<https://github.com/motemen/gore>) Golang的交互式解释器(REPL)
	- [prometheus/prometheus](<https://github.com/prometheus/prometheus>) 系统和服务监控系统
	- [rakyll/hey](<https://github.com/rakyll/hey>) Web应用负载测试工具
	- [dinedal/textql](<https://github.com/dinedal/textql>) 用SQL语句从结构化文本中(如CSV/TSV)查询数据
- 网络相关
	
	- [yinghuocho/gotun2socks](<https://github.com/yinghuocho/gotun2socks>) Golang 实现的 tun2socks (推荐)
	- [eycorsican/go-tun2socks](< https://github.com/eycorsican/go-tun2socks>) Golang 实现的 tun2socks
	- [FlowerWrong/tun2socks](<https://github.com/FlowerWrong/tun2socks>) Golang 实现的 tun2socks
	- [songgao/water](<https://github.com/songgao/water>) TUN/TAP 库
	- [xtaci/kcptun](<https://github.com/xtaci/kcptun>) kcptun
	- [xtaci/kcp-go](<https://github.com/xtaci/kcp-go>) kcp-go
	- [google/gopacket](<https://github.com/google/gopacket>) 数据包处理
	- [libp2p/go-libp2p](<https://github.com/libp2p/go-libp2p>) Golang 实现的 libp2p
	- [getqujing/qtunnel](<https://github.com/getqujing/qtunnel>) qTunnel
	- [vzex/dog-tunnel](<https://github.com/vzex/dog-tunnel>) 基于kcp的p2p端口映射工具,同时支持socks5代理
	- [miekg/dns](<https://github.com/miekg/dns>) DNS库
- 安全相关

  - [yahoo/gryffin](<https://github.com/yahoo/gryffin>) Web漏扫
  - [elazarl/goproxy](<https://github.com/elazarl/goproxy>) 可以用这个库开发类似Burp/Fiddler2的工具(或进行中间人测试)
  - [malfunkt/hyperfox](<https://github.com/malfunkt/hyperfox>) 在LAN上代理和记录HTTP/HTTPS的安全工具
  - [future-architect/vuls](<https://github.com/future-architect/vuls>) 漏扫
  - [lesnuages/hershell](<https://github.com/lesnuages/hershell>) 反弹shell
  - [SaturnsVoid/GoBot2](<https://github.com/SaturnsVoid/GoBot2>) Botnet PoC
  - [magisterquis/sshhipot](<https://github.com/magisterquis/sshhipot>) SSH蜜罐
  - [txn2/n2proxy](<https://github.com/txn2/n2proxy>) 可进行简单的内容审计的反向代理
- VPN和代理相关

  - [txthinking/brook](<https://github.com/txthinking/brook>) 跨平台VPN
  - [kanocz/lcvpn](<https://github.com/kanocz/lcvpn>) 轻量级的简单VPN
  - [bigeagle/gohop](<https://github.com/bigeagle/gohop>) 支持加密和流量混淆,反DPI审查
  - [GoVPN](<http://www.govpn.info/>) 非Github项目,同样支持加密和流量混淆及反DPI审查
  - [shadowsocks/shadowsocks-go](<https://github.com/shadowsocks/shadowsocks-go>) Golang 版 Shadowsocks
- 数据库
	
  - [cayleygraph/cayley](<https://github.com/cayleygraph/cayley>) 图形数据库
  - [dgraph-io/dgraph](<https://github.com/dgraph-io/dgraph>) 图形数据库
  - [xo/usql](<https://github.com/xo/usql>) 支持多种数据库的通用命令行程序
- Web框架
  
  
  - [astaxie/beego](<https://github.com/astaxie/beego>) Beego
- GUI相关
  
  - [andlabs/ui](<https://github.com/andlabs/ui>) Platform-native GUI library for Go. (需要CGO支持)
  - [therecipe/qt](<https://github.com/therecipe/qt>) Qt binding for Go
- 其他
  - [tinygo-org/tinygo](<https://github.com/tinygo-org/tinygo>) 一个Go编译器,主要用于微控制器,WebAssembly(WASM)和命令行工具等小型场景



## 其他Awesome-Go

- [avelino/awesome-go](<https://github.com/avelino/awesome-go>) (https://awesome-go.com/)
- [rakyll/go-hardware](<https://github.com/rakyll/go-hardware>) 硬件相关
- [gostor/awesome-go-storage](<https://github.com/gostor/awesome-go-storage>) 存储/数据库相关



## 说明

暂未详细分类整理,主要是记录一下偶然发现的并且好用的资源,避免后续忘记.

列表中存在一些明显过时的或已经有更好方案来代替的项目,但仍记录在此的原因是为了感谢他们曾给我带来一些思路和灵感.