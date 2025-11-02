# Jaemoo Choi's Personal Homepage

Personal academic homepage built with Jekyll and deployed on GitHub Pages.

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions.

### Automatic Deployment

1. Push changes to the `main` or `master` branch
2. GitHub Actions automatically builds the Jekyll site
3. The built site is deployed to the `gh-pages` branch
4. GitHub Pages serves the site at https://jaemoo-choi.github.io

### GitHub Pages Configuration

To enable GitHub Pages for this repository:

1. Go to repository Settings → Pages
2. Under "Build and deployment":
   - Source: Deploy from a branch
   - Branch: `gh-pages`
   - Folder: `/ (root)`
3. Save the settings

The first deployment will automatically create the `gh-pages` branch when you merge changes to `main`.

## 🛠️ Local Development

### Prerequisites

- Ruby (version 3.2 or higher)
- Bundler

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/jaemoo-choi/jaemoo-choi.github.io.git
   cd jaemoo-choi.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Build and serve locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open http://localhost:4000 in your browser

### Building for Production

```bash
JEKYLL_ENV=production bundle exec jekyll build
```

The site will be built to the `_site` directory.

## 📝 Content Updates

- **About Page**: Edit `_pages/about.md`
- **Site Configuration**: Edit `_config.yml`
- **Publications**: Update `_bibliography/papers.bib`
- **Blog Posts**: Add new posts to `_posts/`

## 📦 Key Dependencies

- Jekyll 4.4.1
- jekyll-scholar (for publications)
- jekyll-paginate-v2
- jekyll-github-metadata

## 📄 License

See [LICENSE](LICENSE) file for details.
