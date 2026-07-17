# 考研一轮学习日程

一个无需后端的静态学习日程应用，支持手机与桌面端。完成状态、实际休息日和顺延任务均保存在当前浏览器的 `localStorage` 中。

## 本地查看

直接打开 `index.html` 即可使用；也可以在目录中启动任意静态文件服务器。

## GitHub Pages 部署

仓库已包含 Pages 工作流。首次部署时，在仓库的 **Settings → Pages → Build and deployment** 中将 Source 设为 **GitHub Actions**。此后推送到 `main` 会自动部署，工作流也支持手动触发。

> 浏览器数据仅保存在当前设备和当前站点中，不会自动跨设备同步。
