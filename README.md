# pujaltes.github.io

Personal academic website for Sebastian Pujalte Ojeda.

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000

## Structure

- `index.html` - Homepage with profile, education, experience, and selected publications
- `_pages/publications.md` - Full publications list
- `_pages/blog.md` - Blog listing
- `_bibliography/papers.bib` - BibTeX file for publications
- `_posts/` - Blog posts (markdown)
- `assets/img/profile.jpg` - Profile photo (add your own)
- `assets/pdf/cv.pdf` - CV PDF (add your own)

## Adding Content

### Publications

Edit `_bibliography/papers.bib` to add publications. Use `selected={true}` to feature a paper on the homepage.

### Blog Posts

Create new files in `_posts/` with the format `YYYY-MM-DD-title.md`.

## Deployment

Push to `main` branch. GitHub Actions will automatically build and deploy to GitHub Pages.
