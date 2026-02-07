# Olga Kairienė - Asmeninis Prekės Ženklas

Modern website for Olga Kairienė - personal branding and employee ambassadorship consultant.

## 🚀 Features

- **Fast & Modern**: Built with Astro for excellent performance
- **SEO Optimized**: Proper meta tags, Open Graph, and semantic HTML
- **Responsive**: Works on all devices
- **Easy CMS**: Blog posts managed through markdown/code
- **Lithuanian**: Full Lithuanian language support

## 🛠️ Tech Stack

- [Astro](https://astro.build/) - Static site generator
- [MDX](https://mdxjs.com/) - Markdown with components
- CSS - Custom design system

## 📝 Content Management

### Adding Blog Posts

Edit the blog posts array in:
- `src/pages/blog/index.astro` - for the listing
- `src/pages/blog/[slug].astro` - for full content

### Updating Pages

Each page is a separate `.astro` file in `src/pages/`:
- `index.astro` - Home page
- `apie.astro` - About page
- `paslaugos.astro` - Services page
- `kontaktai.astro` - Contact page

## 🏃‍♂️ Running Locally

```bash
npm install
npm run dev
```

## 🏗️ Building

```bash
npm run build
```

Output will be in `dist/` folder.

## 📦 Deployment

This site is configured for deployment on [Render](https://render.com/):

1. Connect your GitHub repository
2. Render will auto-detect the `render.yaml` configuration
3. Site will be built and deployed automatically

## 📧 Contact Form

The contact form is set up for Netlify Forms but can be adapted to:
- Formspree
- Render form handling
- Custom backend

## 📁 Project Structure

```
/
├── public/
│   └── images/         # Static images
├── src/
│   ├── components/     # Reusable components
│   ├── layouts/        # Page layouts
│   ├── pages/          # All pages
│   │   └── blog/       # Blog pages
│   └── styles/         # Global styles
├── astro.config.mjs
├── package.json
└── render.yaml
```

---

Created with ❤️ for Olga Kairienė
