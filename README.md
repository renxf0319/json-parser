# JSON 解析器 · Online JSON Parser

> 🚀 在线体验：https://renxf0319.github.io/json-parser/
> 📦 源码仓库：https://github.com/renxf0319/json-parser

一个简洁、优雅、功能强大的 JSON 在线解析工具。纯前端实现，数据完全在本地处理，不上传任何服务器，可离线使用。

## ⭐ 感谢点 Star

如果这个项目对你有帮助，**欢迎点一下 Star ⭐** —— 这是对我最大的鼓励和支持，也会让更多人看到这个工具。

你的支持会直接推动我持续优化：新增功能、修复问题、适配移动端与明暗主题。

<p align="center">
  <a href="https://github.com/renxf0319/json-parser/stargazers">
    <img src="https://img.shields.io/github/stars/renxf0319/json-parser?style=social" alt="GitHub stars" />
  </a>
</p>

## ✨ 功能特性

- **格式化（美化）**：将压缩的 JSON 按 2 空格缩进美化，便于阅读。
- **压缩（Minify）**：去除所有空白，生成单行紧凑 JSON。
- **校验**：快速判断 JSON 是否合法，并精确定位错误所在的「行 / 列」。
- **语法高亮**：对键、字符串、数字、布尔、null 进行配色区分。
- **树形视图**：可折叠 / 展开的层级结构，支持「展开全部 / 收起全部」。
- **搜索**：在树形视图中高亮匹配的关键字。
- **复制 / 下载**：一键复制结果或下载为 `formatted.json`。
- **示例 / 上传 / 粘贴**：快速载入示例、从文件读取或粘贴剪贴板内容。
- **明暗主题**：右上角一键切换，偏好会被记住。
- **自动保存**：输入内容暂存在本地，刷新不丢失。

## 🛡️ 隐私

所有解析均在浏览器本地完成，不会向任何服务器发送你的数据。

## 🚀 本地运行

无需构建步骤，直接用浏览器打开 `index.html` 即可：

```bash
# 任选其一
open index.html              # macOS
start index.html             # Windows
xdg-open index.html          # Linux
```

或启动一个本地静态服务器：

```bash
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000
```

## 📦 部署

本项目为纯静态站点，可直接托管于 GitHub Pages / Vercel / Netlify / Cloudflare Pages 等任意静态托管服务。

## 🧩 技术栈

- 原生 HTML / CSS / JavaScript，零依赖、零构建。
- 单文件 `index.html`，便于分发与部署。
