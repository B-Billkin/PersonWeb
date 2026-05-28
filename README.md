# PersonWeb

Hollow 的个人网站，静态 HTML 页面，可直接部署到 GitHub Pages。

## 页面结构

| 文件 | 说明 |
|------|------|
| `index.html` | 首页（作品集主页） |
| `Self.html` | 个人介绍 |
| `Project.html` | 项目展示 |
| `Share.html` | 分享与资源 |
| `picture/` | 图片与静态资源 |
| `drafts/` | 设计草稿与测试页面 |

## 本地预览

直接用浏览器打开 `index.html`，或使用本地服务器：

```bash
# Python 3
python -m http.server 8080

# Node.js (需安装 npx)
npx serve .
```

然后访问 http://localhost:8080

## 部署到 GitHub Pages

1. 在 GitHub 创建新仓库（例如 `PersonWeb`）
2. 将本项目推送到仓库
3. 进入仓库 **Settings → Pages**
4. **Source** 选择 `Deploy from a branch`
5. **Branch** 选择 `main`，目录选 `/ (root)`
6. 保存后等待几分钟，站点会发布到 `https://<用户名>.github.io/<仓库名>/`

## 技术栈

- 纯 HTML / CSS / JavaScript
- [Tailwind CSS](https://tailwindcss.com/)（CDN）
- [Font Awesome](https://fontawesome.com/)（CDN）
- Google Fonts
