# sercanc.github.io

Personal website for Dr. Sercan Ceyhan — Water Resources Engineer & AI/Data Consultant

## Site Structure

```
.
├── _config.yml          # Jekyll configuration
├── _posts/              # Blog posts (add .md files here)
├── assets/              # Images, PDFs, and other files
│   ├── profile.jpg      # Profile photo
│   └── biography.txt    # Bio source
├── index.md             # Home/About page
├── projects.md          # Projects & Research
├── resume.md            # Resume page
├── blog.md              # Blog listing page
└── resume.pdf           # Downloadable resume
```

## Adding Blog Posts

Create a new markdown file in `_posts/` with the naming format:

```
YYYY-MM-DD-title-of-post.md
```

Example front matter:

```yaml
---
layout: post
title: "Your Post Title"
date: 2025-01-15
categories: [category1, category2]
tags: [tag1, tag2]
---

Your content here...
```

## Local Development

1. Install Ruby and Bundler
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Visit `http://localhost:4000`

## Deployment

Simply push to the `main` branch. GitHub Pages will automatically build and deploy the site.

## Theme

Using the [Minima](https://github.com/jekyll/minima) theme, which is natively supported by GitHub Pages.
