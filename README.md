<div align="center">
   <img src="https://mias.moe/favicon.svg" alt="blog-logo" width="300" />
</div>

# Personal Blog

This is [AsperforMias](mailto:asperformias000@gmail.com)'s astro blog with [koibumi](https://github.com/koibumi-design/astro-blog) theme.

## Feature

- ⚡️ 便携的静态页面生成
- 🔍 良好的**SEO**支持
- 📱 响应式设计，适配各种设备(ps:我没做移动端各种像素比例的样式适配)
- ✍️ **Markdown**支持，便于内容创作

## Tech Stacks

- **框架**: [Astro](https://astro.build/)
- **语言**: [TypeScript](https://www.typescriptlang.org/)
- **样式**: [Tailwind CSS](https://tailwindcss.com/)
- **包管理**: [PNPM](https://pnpm.io/)
- **构建工具**: [Vite](https://vitejs.dev/) (由 Astro 内置)
- **部署**: [GitHub Actions](https://github.com/features/actions)

## 本地开发

克隆仓库并安装依赖：

```bash
git clone https://github.com/yourusername/mias.moe.git
cd mias.moe
pnpm install
```

启动开发服务器：

```bash
pnpm dev
```

预览构建结果：

```bash
pnpm build
```

预览构建结果：

```bash
pnpm preview
```

## 部署

本项目通过 GitHub Actions 自动部署，每次推送到 main 分支时会触发构建和部署流程

### License

[MIT](./LICENSE)
