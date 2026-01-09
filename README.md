# Bobby Galli's Blog

My personal blog built with [Astro](https://astro.build), featuring articles on software development, web technologies, and more.

**Live site:** [bobbyg603.com](https://bobbyg603.com)

## Tech Stack

- **Framework:** [Astro](https://astro.build) v5
- **Styling:** [Tailwind CSS](https://tailwindcss.com) v4
- **Content:** MDX for rich markdown with components
- **Deployment:** GitHub Pages

## Project Structure

```
/
├── public/
│   └── pictures/blog/    # Blog post images
├── src/
│   ├── assets/           # Static assets
│   ├── components/       # Reusable Astro components
│   ├── content/
│   │   └── blog/         # MDX blog posts
│   ├── layouts/          # Page layouts
│   ├── pages/            # Route pages
│   └── styles/           # Global styles
└── package.json
```

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Writing Blog Posts

Blog posts are written in MDX and stored in `src/content/blog/`. Each post requires frontmatter:

```mdx
---
title: "Your Post Title"
description: "A brief description"
pubDate: 2024-01-15
category: "Software Development"
tags: ["javascript", "web-development"]
heroImage: "/pictures/blog/your-post-slug/hero.jpg"
---

Your content here...
```

## License

All rights reserved. Blog content and code are proprietary.

## Connect

- [X](https://x.com/bobbyg603)
- [GitHub](https://github.com/bobbyg603)
- [Medium](https://bobbyg603.medium.com)
