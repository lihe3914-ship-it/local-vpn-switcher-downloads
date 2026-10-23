# 本地 VPN 出口切换器 · 公开下载

无需登录 GitHub，下载后可直接转发给同事。

| 系统 | 下载 | 启动 / 停止 |
| --- | --- | --- |
| Windows 10/11 · x64 | [Windows ZIP](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases/download/v1.0.0/local-vpn-switcher-1.0.0-windows-x64.zip) | Start.cmd / Stop.cmd |
| macOS 13.5+ · Apple M 系列 | [Mac Apple 芯片 ZIP](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases/download/v1.1.0/local-vpn-switcher-1.1.0-macos-arm64.zip) | Start.command / Stop.command |
| macOS 13.5+ · Intel | [Mac Intel ZIP](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases/download/v1.1.0/local-vpn-switcher-1.1.0-macos-x64.zip) | Start.command / Stop.command |

[所有版本与校验和](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases)

完整解压，再运行对应启动文件。运行环境已内置，无需安装 Node.js。请自行安装 VPN 客户端，完成登录并填写自己的路径、端口和控制接口。

管理页面：http://127.0.0.1:17896/ · 固定 HTTP/HTTPS 代理：127.0.0.1:17897

Mac 接管与恢复系统代理时会请求管理员授权。Mac 包未做 Apple Developer ID 签名或公证，首次运行请按系统提示允许打开，详见包内 MAC-README.md。订阅在 FlClash 客户端中选择。

包内不含开发者的 VPN 订阅、账号密钥、日志或公司 VPN 注册配置。请转发原始压缩包，不要转发使用后生成的 data/ 文件夹。

此仓库只维护公开分发包与说明；开发源码仓库独立保持私有。真实 VPN 连通性还取决于使用者自己的客户端、账号和网络。