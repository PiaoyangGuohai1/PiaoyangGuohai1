# 飘洋过海的个人主页部署指南

这个仓库包含 `index.html` 主页文件。要在 GitHub 上看到它的效果，可以按照下面的步骤启用 GitHub Pages：

1. 打开仓库页面，点击右上角的 **Settings**。
2. 左侧找到 **Pages** 菜单。
3. 在 **Build and deployment** 里将 Source 选择为 **Deploy from a branch**。
4. 在 Branch 区域选择 `main` 分支和 `/ (root)` 目录，然后保存。
5. 等待几分钟，GitHub 会生成访问地址，通常是 `https://<你的用户名>.github.io/<仓库名>/`。

发布完成后就可以通过生成的链接访问主页了。如果想让它作为个人主页展示在 `https://<你的用户名>.github.io/`，可以将仓库重命名为 `<你的用户名>.github.io`，或在已有的个人站点仓库中放置此页面。

## 本地预览

在发布之前，你也可以在本地浏览器里直接打开 `index.html` 文件查看效果：

```bash
# 克隆仓库后
open index.html         # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

祝你使用愉快！
