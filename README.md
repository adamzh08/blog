# Portfolio Blog Starter

This is a porfolio site template complete with a blog. Includes:

- MDX and Markdown support
- Optimized for SEO (sitemap, robots, JSON-LD schema)
- RSS Feed
- Dynamic OG images
- Syntax highlighting
- Tailwind v4
- Vercel Speed Insights / Web Analytics
- Geist font

## Demo

https://portfolio-blog-starter.vercel.app

```
📦 Blog
.gitignore
├─ README.md
├─ app
│  ├─ blog
│  │  ├─ [slug]
│  │  │  └─ page.tsx
│  │  ├─ page.tsx
│  │  ├─ posts.json
│  │  └─ utils.ts
│  ├─ components
│  │  ├─ footer.tsx
│  │  ├─ mdx.tsx
│  │  ├─ nav.tsx
│  │  └─ posts.tsx
│  ├─ global.css
│  ├─ layout.tsx
│  ├─ not-found.tsx
│  ├─ og
│  │  └─ route.tsx
│  ├─ page.tsx
│  ├─ robots.ts
│  ├─ rss
│  │  └─ route.ts
│  └─ sitemap.ts
├─ package-lock.json
├─ package.json
├─ pnpm-lock.yaml
├─ postcss.config.js
└─ tsconfig.json
```

## How to Use

You can choose from one of the following two methods to use this repository:

### One-Click Deploy

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=vercel-examples):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/examples/tree/main/solutions/blog&project-name=blog&repository-name=blog)

### Clone and Deploy

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [pnpm](https://pnpm.io/installation) to bootstrap the example:

```bash
pnpm create next-app --example https://github.com/vercel/examples/tree/main/solutions/blog blog
```

Then, run Next.js in development mode:

```bash
pnpm dev
```

Deploy it to the cloud with [Vercel](https://vercel.com/templates) ([Documentation](https://nextjs.org/docs/app/building-your-application/deploying)).
