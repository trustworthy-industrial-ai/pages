# Article images

To add a supporting graphic to an article card:

1. Create a folder here named after the article's slug (the filename after the date in `_posts/`):
   `assets/articles/<slug>/cover.jpg` (or `.png`)
2. Add `image: /assets/articles/<slug>/cover.jpg` to that article's front matter in `_posts/`.
3. Rebuild — the homepage card and post page will pick it up automatically. No image = plain text card, no error.

Example:

```
_posts/2026-07-09-ai-predicts-agents-act-who-decides.md
assets/articles/ai-predicts-agents-act-who-decides/cover.jpg
```

```yaml
---
title: "AI predicts. Agents act. But who decides?"
image: /assets/articles/ai-predicts-agents-act-who-decides/cover.jpg
---
```
