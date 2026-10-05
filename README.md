# jiayuewan.com

Personal website of Jiayue Wan, built with [Hugo](https://gohugo.io) (no theme; layouts live in this repo) and deployed on Netlify.

## Editing content

| What | Where |
| --- | --- |
| Bio (homepage text) | `content/_index.md` |
| Name, role, social links, CV link, SEO description | `hugo.toml` → `[params]` |
| Interests & education | `data/profile.yaml` |
| Experience | `data/experience.yaml` |
| Publications | `content/publication/<slug>/index.md` (one folder per paper) |
| Talks (hidden by default) | `data/talks.yaml`; set `showTalks = true` in `hugo.toml` |
| Photo / favicon | `assets/images/avatar.jpg`, `assets/images/icon.png` |
| CV and slides (PDFs) | `static/uploads/` |
| Styles and colors (`--accent`, `--bg`, … tokens at the top) | `assets/css/main.css` |
| Fonts (Inter, Source Serif 4, self-hosted) | `static/fonts/` |

### Adding a publication

Create `content/publication/my-paper/index.md`:

```yaml
---
title: "Paper Title"
date: 2026-01-01
authors:
  - "Jiayue Wan*"      # trailing * = equal contribution; your name is bolded automatically
  - "Coauthor Name*"
venue: "*Journal Name* 1(2)"   # Markdown allowed
type: journal                  # journal | conference | preprint
doi: 10.xxxx/xxxxx              # optional; adds a DOI button
links:
  pdf: https://...
  code: https://...
abstract: "..."
---
```

Publications are listed newest first by `date`.

### Updating the CV

Drop the new PDF in `static/uploads/` and point the `cv` param in `hugo.toml` at it (this updates both the menu and the homepage CV button). Optionally add a redirect from the old filename in `netlify.toml`.

## Local preview

Requires Hugo ≥ 0.156 (`brew install hugo`).

```sh
hugo server        # http://localhost:1313
```

## Deploy

Netlify builds with the command and Hugo version in `netlify.toml` on every push to `master`.
