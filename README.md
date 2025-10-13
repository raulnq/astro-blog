# Raul's Blog

A personal blog built with Astro featuring clean design, dark mode support, and AI-generated content for educational purposes.

🌐 **Live Site**: [https://blog.raulnq.win/](https://blog.raulnq.win/)

## About This Blog

This is my personal blog where I share thoughts, tutorials, and experiments. Most content is generated with AI assistance for educational and experimental purposes. Built on the excellent Astro Zen Blog template by [larry-xue](https://github.com/larry-xue/astro-zen-blog).

## Features

- � Built with Astro for optimal performance
- �📝 Markdown/MDX support for easy content creation
- 🎨 Clean, minimalist design with dark mode
- 🏷️ Tag-based post organization
- 🔍 SEO optimized and fully responsive
- � RSS feed support
- �🔗 Social media integration
- ⚡ Fast loading and great lighthouse scores
- 🤖 AI-assisted content generation
- � Easy content management

## Tech Stack

- **Framework**: [Astro](https://astro.build/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Content**: Markdown with frontmatter
- **Deployment**: Web hosting platform
- **Language**: TypeScript

## Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/raulnq/astro-blog.git
   cd astro-blog
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:4321](http://localhost:4321) in your browser

## Content Creation

### Writing Posts

Create new blog posts in `src/content/blog/` using this frontmatter structure:

```markdown
---
title: "Your Post Title"
description: "Brief description"
date: 2025-01-01
tags: ["programming", "astro"]
source: "https://original-source.com" # Optional: link to original source
---

Your content here...
```

### Quick Post Creation

Use the provided script to create new posts:

```bash
npm run new-post your-post-title
```

## Project Structure

```
astro-blog/
├── src/
│   ├── content/
│   │   └── blog/         # Blog posts (Markdown files)
│   ├── layouts/          # Page layouts
│   ├── components/       # Reusable UI components
│   ├── pages/           # Site pages and routing
│   ├── utils/           # Utility functions
│   └── config.ts        # Site configuration
├── public/              # Static assets
└── astro.config.mjs     # Astro configuration
```

## Contact

- **Website**: [https://blog.raulnq.win/](https://blog.raulnq.win/)
- **GitHub**: [@raulnq](https://github.com/raulnq)
- **LinkedIn**: [raulnq](https://www.linkedin.com/in/raulnq)
- **Email**: raulnq@gmail.com

## Credits

This blog is built using the excellent [Astro Zen Blog](https://github.com/larry-xue/astro-zen-blog) template by [@larry-xue](https://github.com/larry-xue).

## License

This project is licensed under the MIT License - see the LICENSE file for details.
