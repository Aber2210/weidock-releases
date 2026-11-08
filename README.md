# WeiDock Releases

微坞 WeiDock 的发布产物与更新源。**源代码仓库为私有**，本仓只存放可分发的二进制与更新 feed。

## 下载

| 版本 | 形态 | 文件 |
|---|---|---|
| 3.6.0 | Electron 免安装 | `WeiDock-3.6.0-win-x64-electron.zip` |
| 3.6.0 | Tauri 免安装 | `WeiDock-3.6.0-win-x64-portable.exe` |

## 更新源

应用内「设置 → 关于 → 更新源」填以下任一地址：

```
https://github.com/Aber2210/weidock-releases/releases/latest/download/update-electron.json
https://github.com/Aber2210/weidock-releases/releases/latest/download/update-tauri.json
```

feed 字段：`version` / `url` / `sha256` / `notes` / `publishedAt`。
下载后请用 `SHA256SUMS` 或 feed 里的 `sha256` 校验。

## 许可

MIT（见源码仓 `LICENSE`）。预置平台名称与标识的权利归各平台所有者。
