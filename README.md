# 本地 VPN 出口切换器 · 公开下载

在 FlClash、Cloudflare WARP 和其他本机代理之间切换，支持连接检测、系统代理接管和原网络恢复。无需登录 GitHub 即可下载或转发。

## 下载并安装

| 电脑 | 下载 v1.2.0 | 解压后双击 |
| --- | --- | --- |
| Windows 10/11 · Intel / AMD 64 位 | [Windows x64 ZIP](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases/download/v1.2.0/local-vpn-switcher-1.2.0-windows-x64.zip) | **Install.cmd** |
| Mac · Apple M 系列芯片 · macOS 13.5+ | [Mac arm64 ZIP](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases/download/v1.2.0/local-vpn-switcher-1.2.0-macos-arm64.zip) | **Install.command** |
| Mac · Intel 芯片 · macOS 13.5+ | [Mac x64 ZIP](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases/download/v1.2.0/local-vpn-switcher-1.2.0-macos-x64.zip) | **Install.command** |

1. 下载对应版本并完整解压，不要在 ZIP 内直接运行。
2. 双击表格中的安装文件，自动复制程序并创建桌面“VPN 出口切换器”和“VPN 恢复网络并退出”两个入口。安装不需要管理员权限，也不设置开机自启。
3. 双击桌面“VPN 出口切换器”打开页面，填写自己的客户端路径、代理端口及控制接口。VPN 客户端和订阅需自行准备；首次登录和连接在原客户端完成。
4. 使用结束后双击“VPN 恢复网络并退出”，等待原网络恢复。只关闭网页不会停止后台服务。

运行环境已内置，无需安装 Node.js。安装后可删除 ZIP 和解压目录；以后直接使用桌面入口。

## 安装位置、更新和卸载

- **Windows**：安装到 `%LOCALAPPDATA%\LocalVpnSwitcher`，开始菜单提供启动、恢复网络和卸载入口，也可运行安装目录的 `Uninstall.cmd`。
- **Mac**：安装到 `~/Applications/Local VPN Switcher`；卸载时在该目录双击 `Uninstall.command`。
- **更新**：重新运行新版本的安装文件，保留 `data/` 个人配置。卸载同样保留个人配置，便于以后重新安装。
- **免安装**：仍可直接使用解压包中的 `Start.cmd` / `Stop.cmd`；Mac 使用 `Start.command` / `Stop.command`，运行期间保留解压目录。

Mac 修改系统代理时会请求管理员授权。Mac 包未做 Apple Developer ID 签名或公证，首次运行请按系统提示允许打开，详见包内 `MAC-README.md`。订阅在 FlClash 客户端中选择。

[最新版本与 SHA-256 校验和](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases/latest) · [所有历史版本](https://github.com/lihe3914-ship-it/local-vpn-switcher-downloads/releases)

管理页面：http://127.0.0.1:17896/ · 固定 HTTP/HTTPS 代理：127.0.0.1:17897

原始发布包不含个人 VPN 订阅、账号密钥、日志或公司注册配置。转发时使用原始 ZIP，避免分享运行后生成的 `data/`。此仓库只维护公开下载和说明；源码独立保持私有。
