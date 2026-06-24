# Valerie Brown – Heat & Climate Resilience Expert

Personal website for Valerie Brown, built with [Hugo](https://gohugo.io) and the [Celadon](https://github.com/Yajie-Xu/hugo-celadon) theme. Deployed on Cloudflare Pages.

## Site Structure

| Page | URL | Description |
|---|---|---|
| Home | `/` | Profile, recent engagements, and recent publications |
| Research | `/research/` | Full publications list organized by theme |
| Resume | `/resume/` | Full CV with work experience and education |

## Content files

- `data/profile.yaml` — Name, bio, expertise list, links
- `data/news.yaml` — Recent speaking engagements and events
- `data/research.yaml` — Publications shown on the homepage
- `content/research.md` — Full research/publications page
- `content/resume.md` — Full resume page

## Local development

Requires [Hugo extended](https://gohugo.io/installation/) v0.112+.

```bash
hugo server
```

Open [http://localhost:1313](http://localhost:1313) to preview.

## Deployment

This site is deployed via **Cloudflare Pages**.

| Setting | Value |
|---|---|
| Build command | `hugo --minify` |
| Build output directory | `public` |
| Hugo version | Set `HUGO_VERSION` environment variable (e.g. `0.163.1`) |

## Theme

[Celadon](https://github.com/Yajie-Xu/hugo-celadon) by Yajie Xu, included as a git submodule.

## License

Copyright © 2026 Valerie Brown. All rights reserved.  
Content, text, and images on this site may not be reproduced without explicit written permission.

The Celadon theme is licensed separately under its own [MIT license](themes/celadon/LICENSE.txt).
