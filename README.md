# turygo.github.io

个人博客「一个人的盛宴」，基于 [Astro](https://astro.build) + [Fuwari](https://github.com/saicaca/fuwari) 主题。

## 常用命令

```sh
pnpm install        # 安装依赖
pnpm dev            # 本地开发 (localhost:4321)
pnpm new-post <name> # 新建文章 src/content/posts/<name>.md
pnpm build          # 构建到 dist/
```

## 部署

推送到 `hugo` 分支后由 GitHub Actions 自动构建并发布到 GitHub Pages（见 `.github/workflows/deploy.yml`）。

首次启用需在仓库 Settings → Pages 中把 Source 设为 **GitHub Actions**，并确认自定义域名 `turygo.com`。
