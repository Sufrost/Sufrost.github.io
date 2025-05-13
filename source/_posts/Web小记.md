---
title: Web小记
date: 2025-05-14 00:32:38
tags: [Web,前端]
categories: 技术
---

这是我的第一篇Hexo文章！

写标签时一定要在冒号后面加空格！一直在找错，结果发现是没加空格。

在提交前，你可以在本地运行 Hexo 服务器预览效果：

```bash
hexo server  # 启动本地服务器
# 访问 http://localhost:4000 查看效果
```

按 `Ctrl+C` 停止服务器。

### **3. 提交到 GitHub**

使用 Git 将更改提交到远程仓库：

```bash
# 1. 添加所有更改到暂存区
git add .
# 2. 提交更改（添加有意义的提交信息）
git commit -m "Add new post: HelloWorld"
# 3. 推送到 GitHub 远程仓库
git push origin main  # 假设主分支名为 main
```

每次添加或修改文章后，只需执行：

```bash
git add _posts/  # 添加所有文章变更
git commit -m "Update posts"
git push origin main
```

GitHub Actions 会自动处理部署，无需手动干预。
