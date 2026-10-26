# Snap 宣传网站

[在线查看](https://shuaishuaisylas.github.io/fip-website/) · [产品功能说明](docs/index.html)

Snap 是围绕项目上下文、工具执行和知识沉淀的桌面 Agent 工作台。网站展示 11 项功能及本机真实操作录屏，重点包括上下文引用、执行轨迹与 AI 说明、Todo 和 Obsidian。

## 页面与素材

- `index.html`：宣传页面，包含样式与交互脚本。
- `assets/videos/` 与 `assets/posters/`：11 组演示与封面。演示为静音循环 MP4，内嵌展示隐藏原生控件，并保留暂停与放大入口。
- `docs/index.html`：公开功能说明。
- `assets/brand/snap-logo.png`：Snap 品牌图标，用于页头与 favicon。

页面版本 1.0.5。品牌已更新为 Snap；录屏来自更名前版本，画面中保留旧品牌字样，视频与封面未因更名而重做。录屏此前已清理窗口黑角和左上角操控浮标。分享或移动时请保留相对目录结构。

## 本地预览与发布

无需安装依赖。可直接打开 `index.html`，或在本目录运行：

```sh
python3 -m http.server 8000
```

GitHub Pages 使用 `main` 分支的仓库根目录 `/`。更新并推送文件后会自动重新发布。

为保持现有链接可用，仓库和 Pages 地址继续使用 `fip-website`；功能锚点和浏览器主题存储键也保持不变。

本站用于产品介绍和演示；页面本身不启动 Agent、不请求模型，也不读写项目或 Obsidian Vault。

## 来源与许可

Snap 基于 [Proma](https://github.com/proma-ai/Proma)，页面节奏参考 [Proma 官网](https://proma.cool/)。原 AGPL-3.0 许可与来源信息保留在 [LICENSE](LICENSE) 和 [NOTICE](NOTICE)。
