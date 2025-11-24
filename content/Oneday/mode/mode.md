---
# 必填项 (Essential Fields)

# 1. 文章标题 (用于页面显示和浏览器标签)
title: {{title}}

# 2. 发布日期 (用于排序和 Vercel 缓存)
date: {{date:YYYY-MM-DD}}T{{time:HH:mm:ss}}

# 3. 英文链接 (【关键】避免中文路径导致 404)
slug: {{date:YYYYMMDD}}-{{name-to-slug}}

# 4. 发布状态 (确保文章不会被隐藏)
published: true 
---

# **{{title}}**

## 📝 正文开始

---

在这里开始你的笔记正文内容。

你可以使用标准的 Markdown 语法：
- 这是一个 **粗体**。
- 这是一个 *斜体*。
- 这是一个 [外部链接](https://www.google.com)。

### 引用其他笔记

使用 Obsidian 双向链接：`[[另一篇笔记的名称]]`