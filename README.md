# rlim-fm.github.io

Personal site for Richard F. M. Lim — a single Jekyll page, no JavaScript, one stylesheet.

## Structure

| Path | What it holds |
|---|---|
| `index.html` | The whole page: intro, links, news, projects |
| `_data/news.yml` | News items, newest first. `text` is Markdown |
| `_projects/*.md` | One file per project.  Front matter carries advisors, collaborators, image, and links; the body is the description |
| `assets/css/style.css` | All styling. Colors are custom properties on `:root`, with a dark-mode override |
| `files/CV.pdf` | Linked from the page |

## Adding a project

Copy an existing file in `_projects/`, name it `YYYY-MM-DD-slug.md` (the date is the sort key,
newest first), and fill in the front matter. Every field except `title` and `date` is optional —
omitted sections simply don't render. Link keys render in a fixed order: `paper`, `arxiv`, `code`,
`poster`, `slides`, `bibtex`.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```
