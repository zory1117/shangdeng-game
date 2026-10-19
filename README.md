# 兴宁客家上灯护灯小游戏

本站版本由 [yulele6666-tech/shangdeng-game](https://github.com/yulele6666-tech/shangdeng-game) fork 并适配，保留上游游戏玩法与素材。

在线游玩：**https://wanling1117.top/games/shangdeng/**

本次修改：

- 在原加载画面的进度条下加入 `Created by 欣诺 Powered by Codex`。
- 增加返回个人技术分享网站、原项目来源及备案信息链接。
- 保留键盘、触屏、角色选择、三关护灯、音乐和本地解锁存档。

## 运行与部署

项目使用原生 HTML、JavaScript 和 Canvas，无需 npm 安装或构建。

```bash
python -m http.server 8189 --bind 127.0.0.1
```

浏览器打开 `http://127.0.0.1:8189/`。部署时只需将 `index.html` 与 `assets/` 中运行时 PNG、WAV 文件放在同一目录，可直接通过子目录访问；所有游戏资源均使用相对路径。文档、Git 元数据和部署凭证不属于公开站点文件。

原项目及素材说明保留在上游仓库和 `assets/` 文档中。本 fork 的署名用于本站改编版本，不替代原项目来源。
