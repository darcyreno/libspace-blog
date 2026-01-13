# LibSpace Blog

Official blog for [LibSpace](https://libspace.io) - tips, tutorials, and updates.

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000
```

## Adding a New Post

Create a new file in `_posts/` with the format:

```
YYYY-MM-DD-post-title.md
```

Example front matter:

```yaml
---
title: "Your Post Title"
date: 2026-01-13
author: "LibSpace Team"
image: "https://files.libspace.io/blog/your-image.jpg"
excerpt: "A brief description of your post."
---
```

## RSS Feed

The RSS feed is automatically generated at `/feed.xml`.

Users can subscribe at: `https://blog.libspace.io/feed.xml`

## Deployment

This blog is deployed automatically via GitHub Pages when changes are pushed to the `main` branch.

## Custom Domain

The blog is served at `blog.libspace.io` via the `CNAME` file.
