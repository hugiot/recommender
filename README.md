# Recommender

一个好用的工具集推荐器

## NAS

**编号**

* 功能：为 docker 类服务编号，便于记录端口号分配范围
* -1：导航类特殊服务，默认占用 80 端口

**端口定义**

* 分类：系统端口、映射端口（docker 应用）
* 范围：50000 ~ 59999（可自行调整）
* 单个服务端口范围：0 ~ 9（例如：50000 ~ 50009、50010 ~ 50019）

| 编号 | 类别   | 名称               | 描述                        | 端口                  | 链接                                                                                                             |
|----|------|------------------|---------------------------|---------------------|----------------------------------------------------------------------------------------------------------------|
|    | 系统   |                  |                           |                     |                                                                                                                |
|    |      | 飞牛 fnOS          | 免费的 NAS 系统                | 5666、5667           | [官网](https://www.fnnas.com/)                                                                                   |
|    | 网络   |                  |                           |                     |                                                                                                                |
|    |      | Tailscale        | 基于 WireGuard 的虚拟组网工具      |                     | [官网](https://tailscale.com/)                                                                                   |
|    |      | Headscale        | Tailscale 控制服务器的开源自托管实现   |                     | [官网](https://headscale.net/stable/)                                                                            | 
|    | 办公   |                  |                           |                     |                                                                                                                |
| 0  |      | Nextcloud        | 开源云协作平台（个人云盘）             | 50000:50            | [官网](https://nextcloud.com/)                                                                                   |
| 1  |      | ONLYOFFICE       | 开源的办公套件（可搭配 Nextcloud 使用） | 50001:80            | [官网](https://www.onlyoffice.com/)                                                                              |
|    | 影音   |                  |                           |                     |                                                                                                                |
| 2  |      | LibreTV          | 开源影视站                     | 50010:80            | [github](https://github.com/LibreSpark/LibreTV)                                                                |
| 3  |      | XiaoMusic        | 使用小爱音箱播放音乐                | 50020:8090          | [官网](https://xdocs.hanxi.cc/)、[github](https://github.com/hanxi/xiaomusic)                                     |
| 4  |      | Navidrome        | 个人流媒体服务                   | 50050:4533          | [官网](https://www.navidrome.org/)、[github](https://github.com/navidrome/navidrome)                              |
| 5  |      | Music Tag Web V2 | 音乐标签编辑器                   | 50060:8002          | [官网](https://xiers-organization.gitbook.io/music-tag-web-v2)、[github](https://github.com/xhongc/music-tag-web) |
|    | 导航   |                  |                           |                     |                                                                                                                |
| -1 |      | Sun-Panel        | 开源导航面板                    | 80:3002             | [官网](https://doc.sun-panel.top/zh_cn/)                                                                         |
|    | 休闲娱乐 |                  |                           |                     |                                                                                                                |
| 6  |      | EmulatorJS       | web 游戏模拟器                 | 50030:3000、50031:80 | [官网](https://emulatorjs.org/)                                                                                  |
|    | 下载   |                  |                           |                     |                                                                                                                |
| 7  |      | MediaGo          | 跨平台视频提取工具                 | 50040:8899          | [github](https://github.com/caorushizi/mediago)                                                                |