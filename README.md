# vthorrf.github.io

Personal academic website of **Víthor Rosa Franco**, built with Jekyll and the Academic Pages theme.

## Publish on GitHub Pages

1. Make sure the repository is named exactly `vthorrf.github.io`.
2. Upload/commit the contents of this repository to the repository root.
3. On GitHub, open **Settings → Pages**.
4. Under **Build and deployment → Source**, select **GitHub Actions**.
5. Push to the `main` or `master` branch. The workflow in `.github/workflows/pages.yml` will build and deploy the site.
6. After the workflow completes, the site should be available at `https://vthorrf.github.io`.

## Main content files

- `_pages/about.md` — homepage
- `_pages/research.md` — research page
- `_pages/publications.html` — publication rendering
- `_pages/software.md` — software page
- `_pages/teaching.html` — teaching page
- `_pages/cv.md` — CV page
- `_data/publications.yml` — peer-reviewed publication data
- `_data/book_chapters.yml` — book chapters
- `_data/books.yml` — edited books
- `_data/editorials.yml` — editorials
- `_data/navigation.yml` — top navigation
- `_config.yml` — site-wide profile and links
- `images/profile.jpg` — profile photograph
- `assets/css/main.scss` — theme imports and custom styles

## Add a publication

Add a new item near the top of `_data/publications.yml` using the same fields as the existing records:

```yaml
- status: Published
  year: 2026
  authors: Franco, V. R., & Coauthor, A. B.
  title: Title of the article
  venue: Journal Name, volume, pages
  url: https://doi.org/...
  featured: false
```

Set `featured: true` if the article should also appear in the selected-publications section on the homepage.

## Local preview (optional)

If Ruby and Bundler are installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
