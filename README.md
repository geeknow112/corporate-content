# corporate-content

Source of truth for the corporate site content: https://trident-capital-symbiosis.com/ (WordPress, WP Githuber MD)

## Convention

- Each fixed page lives at `pages/<slug>.md`, where `<slug>` matches the page's slug on WordPress.
- Content is plain Markdown. `biz-tools wp` converts it to HTML and pushes it to the matching WordPress page via the REST API.
- All changes — human or automated — go through this repo (draft branch -> PR -> merge). Nobody edits pages directly in the WordPress admin screen.

## Workflow

```
biz-tools media draft pages/about.md -p wordpress    # branch + PR
biz-tools media publish pages/about.md -p wordpress  # merge PR + push to WordPress
```
