# turygo.github.io

个人博客「一个人的盛宴」，基于 [Astro](https://astro.build) + [Astro Micro](https://github.com/trevortylerlee/astro-micro) 主题。

## 常用命令

```sh
pnpm install        # 安装依赖
pnpm dev            # 本地开发 (localhost:4321)
pnpm build          # 构建到 dist/（含 astro check 与 Pagefind 索引）
pnpm preview        # 预览已构建产物
```

## 写文章

在 `src/content/blog/<slug>/index.md`（或 `.mdx`）新建文章，frontmatter 字段：

```yaml
---
title: 标题
description: 摘要
date: 2026-07-12
tags: [随笔]
draft: false
---
```

## 部署

推送到 `hugo` 分支后由 GitHub Actions 自动构建并发布到 GitHub Pages（见 `.github/workflows/deploy.yml`）。

首次启用需在仓库 Settings → Pages 中把 Source 设为 **GitHub Actions**，并确认自定义域名 `turygo.com`。
