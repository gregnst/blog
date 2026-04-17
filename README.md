# Gregorio Nastasi's Blog

A modern personal blog built with Jekyll and the Chirpy theme, exploring data science, causal inference, and analytics.

## 🚀 Features

- **Chirpy Theme**: Modern, responsive design with dark mode support
- **Causal Inference & Data Science**: Content focused on analytics and insights
- **SEO Optimized**: Built-in SEO tags and sitemap generation
- **Fast & Lightweight**: Static site generation for optimal performance
- **Mobile Responsive**: Works seamlessly on all devices

## 📂 Project Structure

```
blog/
├── _config.yml          # Site configuration
├── _sass/               # Custom SCSS stylesheets
├── assets/              # Images and static files
├── content/             # Blog posts
├── about.md             # About page
├── index.md             # Homepage
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## 🛠️ Setup & Installation

### Prerequisites
- Ruby 2.7+
- Jekyll 4.3+

### Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View your site:**
   Open `http://localhost:4000/blog` in your browser

## ✍️ Writing Posts

Blog posts go in the `content/` directory. Create a new folder with the format `YYYY-MM-title/`:

```
content/
├── 2026-01-queens-gambit/
│   └── 2026-01-queens-gambit.md
├── 2025-06-masters-thesis/
│   └── 2025-06-masters-thesis.md
```

**Post Front Matter Example:**
```yaml
---
layout: post
title: Your Post Title
date: 2026-04-15
categories: [data-science, causal-inference]
tags: [analytics, python]
---

# Your content here
```

## 📱 Navigation

The blog displays only the **About** section in the header navigation. Other pages are accessible via:
- Direct URL: `/about`
- Homepage links
- Blog post navigation

## 🎨 Customization

### Custom Styling
Edit `_sass/custom/custom.scss` for additional CSS overrides.

### Site Configuration
Update `_config.yml` for:
- Site title and description
- Author information
- Social media links
- Theme settings (light/dark mode)

### Colors & Theme
Chirpy uses CSS variables for theming. Edit the theme files or add custom overrides in `_sass/custom/`.

## 🚀 Deployment

This blog is deployed via GitHub Pages. Push changes to the `main` branch:

```bash
git add .
git commit -m "Your commit message"
git push origin main
```

GitHub will automatically build and deploy your site to `https://gregnst.github.io/blog`

## 📚 Resources

- [Chirpy Theme Documentation](https://chirpy.cotes.page/)
- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages Guide](https://pages.github.com/)

## 📝 License

Personal blog © 2026 Gregorio Nastasi

---

**Built with ❤️ using Jekyll + Chirpy**
