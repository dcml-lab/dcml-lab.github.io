# DCML - Research Group Website

A clean, modern website for the Data-Centric Machine Learning (DCML) group at Harvard University.

Built with [Hugo](https://gohugo.io/) for speed and simplicity.

## Quick Start

```bash
# Install Hugo (macOS)
brew install hugo

# Run locally
hugo server

# Build for production
hugo --gc --minify
```

## Adding Content

### Add a Publication from arXiv

> **Citation fields are synced from David's master publication list** (`~/workspace/publications/pubs.bib`). `make dotml` there overwrites `title`, `authors`, `venue`, `year`, `arxiv`, `code` and `bibtex` on every page it matches, so fix those fields in the master, not here. Summaries, abstracts, images and other links stay hand-curated. After creating a page with `add-paper`, run `make dotml` to replace its arXiv-derived metadata with the verified entry.

```bash
# Basic usage
./bin/add-paper --arxiv https://arxiv.org/abs/2309.12345

# With GitHub and video links
./bin/add-paper --arxiv https://arxiv.org/abs/2309.12345 --github https://github.com/org/repo --video https://youtube.com/watch?v=...

# Also create a project page
./bin/add-paper --arxiv https://arxiv.org/abs/2309.12345 --project
```

### Create a Project Page

For featured papers with rich content (like [FloWM](https://flowequivariantworldmodels.github.io/)):

```bash
./bin/create-project --arxiv https://arxiv.org/abs/2309.12345 --name "my-project" --github URL --video URL
```

This creates:
- `content/research/my-project/index.md` - Edit to add method/results
- `static/img/projects/my-project/` - Add figures here

### Add a News Item

```bash
# Quick inline news
./bin/add-news "Paper accepted to NeurIPS! 🎉"

# With custom title
./bin/add-news --title "NeurIPS Acceptance" "Our paper on X was accepted!"
```

### Add a Team Member

```bash
./bin/add-member --name "Jane Doe" --category phd --website https://janedoe.com

# Options: pi, postdoc, phd, masters, undergrad, visiting
./bin/add-member --name "John Smith" --category postdoc --image john.jpg

# Mark as alumni
./bin/add-member --name "Former Student" --category phd --alumni
```

## Project Structure

```
├── content/
│   ├── team/           # Team member pages
│   ├── publications/   # Publications
│   ├── research/       # Project pages
│   ├── news/           # News items
│   └── blog/           # Blog posts
├── static/img/         # Images
├── layouts/            # HTML templates
├── assets/css/         # Styles
└── bin/                # Automation scripts
```

## Customization

### Site Configuration
Edit `hugo.toml` for:
- Site title and description
- Social links (GitHub, Twitter)
- Menu items

### Styling
Edit `assets/css/main.css` for:
- Colors (CSS variables in `:root`)
- Typography
- Component styles

### Templates
- `layouts/index.html` - Homepage
- `layouts/team/list.html` - Team page
- `layouts/research/single.html` - Project page

## Deployment

The site auto-deploys to GitHub Pages on push to `main`/`master` via GitHub Actions.

Manual deployment:
```bash
hugo --gc --minify
# Upload public/ to your host
```

## License

MIT
