# fenxxbme’s notebook

Personal site, published with GitHub Pages / Jekyll. No installation needed.

## 发布一篇文章

在 GitHub 仓库里选择 **Add file → Create new file**。
文件名写成 `_posts/YYYY-MM-DD-your-title.md`，替换为发布日期和文章短标题，例如 `_posts/2026-10-15-first-note.md`。
粘贴下面的模板，填写标题、分类、简介和正文，然后点击 **Commit changes**。部署成功后，文章会自动出现在首页，最新的在最上面。

```markdown
---
layout: post
title: "文章标题"
date: 2026-10-15
category: Thoughts
description: "一句话简介"
lang: zh-CN
---

这里写正文，中英文都可以。

## 小标题

- 可以列要点
- 也可以写代码、插入图片或添加链接
```

分类可以写 `Thoughts`、`Learning notes` 或 `Write-ups`，也可以自定义。只发布你希望公开的内容。将日期设为当天或过去；未来日期的文章默认不会显示。

## 修改首页

编辑 `index.html`。文章样式在 `_layouts/post.html`。`index.html` 顶部的两行 `---` 是 Jekyll 所需的，请保留。

## 预览与发布

每次保存后，查看仓库 Actions 中的 `pages build and deployment`。成功后访问 https://fenxxbme.github.io 。邮箱和 CV 目前为占位。
