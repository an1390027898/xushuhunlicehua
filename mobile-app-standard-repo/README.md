# Mobile App Repository Package

这是整理后的 **标准静态仓库结构**，可直接上传到 GitHub。

## 项目说明

- 入口文件：`index.html`
- 当前版本：移动端优先（手机 / 平板 / 折叠屏）
- 技术形态：纯静态前端（单文件 HTML，可直接本地打开）

## 仓库结构

```text
mobile-app-standard-repo/
├── .gitattributes
├── .gitignore
├── README.md
├── index.html
├── assets/
│   └── images/
├── docs/
│   ├── DEPLOY_TO_GITHUB.md
│   ├── RELEASE_NOTES.md
│   └── original-index-backup.html
└── .github/
    └── workflows/
        └── static-pages.yml
```

## 本地使用

直接双击 `index.html`，或用任意静态服务器打开。

例如：

```bash
python -m http.server 8000
```

然后访问 `http://localhost:8000`

## 上传到 GitHub

请查看：`docs/DEPLOY_TO_GITHUB.md`

## 说明

- 当前仓库为 **静态页面仓库**，没有额外构建步骤。
- 如果后续你要拆分成 `css/`、`js/`、`components/` 结构，我可以继续帮你整理成更工程化版本。
