# Wechatsync - 文章同步助手

![GitHub stars](https://img.shields.io/github/stars/wechatsync/Wechatsync?style=flat-square)
![GitHub release](https://img.shields.io/github/v/release/wechatsync/Wechatsync?style=flat-square)
![License](https://img.shields.io/github/license/wechatsync/Wechatsync?style=flat-square)

**开源免费**的跨平台文章同步工具，一键同步文章到知乎、头条、掘金、小红书、CSDN 等 **29+ 平台**。

## 核心项目

| 仓库 | 说明 |
|------|------|
| [Wechatsync](https://github.com/wechatsync/Wechatsync) | 主仓库 — Chrome 扩展 + MCP Server + CLI |
| [article-syncjs](https://github.com/wechatsync/article-syncjs) | 网页端 JS SDK，支持从任意编辑器发起同步 |

## 它能做什么

- **Chrome 扩展** — 浏览器内一键批量发布文章，支持草稿模式
- **CLI 命令行** — `wechatsync sync article.md -p zhihu,juejin,csdn`
- **MCP Server** — 接入 Claude Desktop / Claude Code，用自然语言发布文章
- **网页转 Markdown** — 智能提取正文，自动打包为 Markdown + 图片 ZIP

## 支持平台

知乎 · 掘金 · CSDN · 头条 · 简书 · 微博 · 小红书 · 抖音 · B站 · 百家号 · 语雀 · 豆瓣 · 搜狐 · 雪球 · 51CTO · SegmentFault · 博客园 · 开源中国 · X (Twitter) · WordPress · Typecho · 更多...

## 设计原则

- **不是爬虫** — 使用你自己浏览器中的登录态，调用平台官方 Web API
- **数据不离开设备** — 没有中间服务器，没有数据上传，源码完全开源
- **草稿优先** — 默认同步为草稿，发布前由你确认

## 快速开始

```bash
# Chrome 扩展（推荐）
# 从 Chrome 网上应用店安装：
# https://chrome.google.com/webstore/detail/hchobocdmclopcbnibdnoafilagadion

# CLI 命令行
npm install -g @wechatsync/cli
```

## 作者

**[fun](https://github.com/lljxx1)** · 独立开发者 · [主页](https://fun0.netlify.app/about/)

---

GPL-3.0 · [文档](https://github.com/wechatsync/Wechatsync#readme) · [提交新平台请求](https://airtable.com/shrLSJMnTC2BlmP29)
