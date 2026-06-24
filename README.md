# Jithin Kanayankottupoyil - Academic Website

Personal academic/professional website built with Markdown, HTML, CSS, JavaScript, Jekyll, and GitHub Pages.

## Purpose

This site presents Jithin Kanayankottupoyil's research, technical work, publications, projects, teaching/workshops, and professional profile in air quality, emissions modeling, regulatory analysis, and machine learning.

## Repository structure

```text
.
├── README.md
├── _config.yml
├── index.md
├── about.md
├── cv.md
├── research.md
├── projects.md
├── publications.md
├── teaching.md
├── blog.md
├── contact.md
├── _layouts/default.html
├── _includes/header.html
├── _includes/footer.html
├── assets/css/style.css
├── assets/js/main.js
├── _posts/2026-06-23-welcome.md
├── files/cv.pdf
├── .gitignore
└── Gemfile
```

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000` in your browser.

## Deployment through GitHub Pages

1. Create a new repository, for example `jithinkp.github.io` or `academic-website`.
2. Upload all files in this repository.
3. Go to **Settings > Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and root folder `/`.
6. Save and wait for GitHub Pages to build the site.

## Customization checklist

- Replace `files/cv.pdf` with the final polished PDF CV.
- Update LinkedIn, Google Scholar, GitHub, ORCID, and email links in `_config.yml`.
- Replace placeholder GitHub username in `_config.yml` and deployment instructions.
- Add project repositories or dataset links once public.
- Add headshot image later under `assets/img/` and update the hero section if desired.
- Add future blog posts under `_posts/` using the format `YYYY-MM-DD-title.md`.
