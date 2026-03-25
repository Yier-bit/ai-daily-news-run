# AI Daily News Run

每日 AI 新闻播客，由 OpenClaw 自动生成。

- 自动搜索聚合最新 AI 新闻
- 生成播客音频
- 部署为静态网站 on GitHub Pages

## 结构

```
index.html             # 首页
style.css              # 样式
audio/                # 音频文件 MP3
articles/             # 文章 HTML
.github/workflows/     # GitHub Action 自动部署
```

## 每日自动生成

OpenClaw 每天自动：
1. 聚合多个 AI 新闻源
2. 生成播客音频
3. 更新网站
4. 推送到 GitHub → 自动部署

https://Yier-bit.github.io/ai-daily-news-run/
