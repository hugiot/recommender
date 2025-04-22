# Recommender

一个好用的工具集推荐器

## NAS

**端口定义**

* 分类：系统端口、映射端口（docker 应用）
* 范围：50000 ~ 59999（可自行调整）
* 单个服务端口范围：0 ~ 9（例如：50000 ~ 50009、50010 ~ 50019）

| 类别 | 名称 | 描述 | 端口 | 链接 |
|-|-|-|-|-|
| 系统 | | | | |
| | 飞牛 fnOS | 免费的 NAS 系统 | 5666、5667 | [官网](https://www.fnnas.com/) |
| 网络 | | | | |
| | Tailscale | 基于 WireGuard 的虚拟组网工具 | | [官网](https://tailscale.com/) |
| | Headscale | Tailscale 控制服务器的开源自托管实现 | | [官网](https://headscale.net/stable/) | 
| 办公 | | | | |
| | Nextcloud | 开源云协作平台（个人云盘） | 50000:50 | [官网](https://nextcloud.com/) |
| | ONLYOFFICE | 开源的办公套件（可搭配 Nextcloud 使用） | 50001:80 | [官网](https://www.onlyoffice.com/) |
| 影音 | | | | |
| | LibreTV | 开源影视站 | 50030:80 | [github](https://github.com/LibreSpark/LibreTV) |
| 导航 | | | | |
|| Sun-Panel | 开源导航面板 | 80:3002 | [官网](https://doc.sun-panel.top/zh_cn/) |
|休闲娱乐 | | | | |
| | EmulatorJS | web 游戏模拟器 | 50020:3000、50021:80 | [官网](https://emulatorjs.org/) |
|下载| | | | |
| | MediaGo |跨平台视频提取工具| 50010:8899| [github](https://github.com/caorushizi/mediago) |