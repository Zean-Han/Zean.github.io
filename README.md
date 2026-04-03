# 个人主页模板

## 如何使用

1. 编辑 `index.html`：替换「你的名字」、各段文字、链接、邮箱。
2. 需要改配色或宽度时，编辑 `styles.css` 顶部的 `:root` 变量。
3. 本地预览：用浏览器直接打开 `index.html`，或运行：
   ```bash
   cd personal-homepage-template && python3 -m http.server 8080
   ```
   然后访问 <http://127.0.0.1:8080>。

## 部署到 GitHub Pages

1. 把本文件夹内容推送到仓库（例如 `username.github.io`）的 **main** 分支根目录，或 **Settings → Pages** 里选择 **Branch + / (root)**。
2. 几分钟后站点一般为 `https://username.github.io`。

## 把仓库设为 Private

需要在 GitHub 网页上操作（无法用本机命令代替你登录）：

1. 打开仓库 → **Settings** → 左侧 **General**。
2. 拉到最下 **Danger zone** → **Change repository visibility** → 选 **Private**。

**注意：** 免费账号下，**Private 仓库的 GitHub Pages 默认不对外公开托管个人站**（或需付费计划，政策以 [GitHub 文档](https://docs.github.com/pages) 为准）。若希望主页**公网可访问**而代码不公开，常见做法是：

- 用 **Public** 仓库只放**编译后的静态页**（无敏感信息），或  
- 使用 **Netlify / Cloudflare Pages** 等从私有仓库部署。

## 与现有 `Zean.github.io` 的关系

若你已有 [Zean.github.io](https://github.com/Zean-Han/Zean.github.io)，可将本模板中的 `index.html` 与 `styles.css` **覆盖**仓库内对应文件后 `git push`，或把整个模板复制进该仓库根目录。
