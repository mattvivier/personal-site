<!--
TEMPLATE FILE -- not a real post.
This lives at the repo root (not inside content/), so Pelican never scans,
builds, or publishes it. Copy what you need into a new file inside content/,
then delete this comment block and any metadata fields you don't use.
-->

Title: My Post Title
Date: 2026-07-23 10:00
Modified: 2026-07-24 09:00
Category: Tech
Tags: pelican, python, meta
Slug: my-post-title
Author: Matt Vivier
Summary: One or two sentences shown in the index/RSS feed instead of an auto-truncated excerpt.
Status: published

<!--
Status options:
  published (default) - normal post, shows in the index and feed
  draft                - built, but excluded from the index/feed; only reachable at a /drafts/... URL
  hidden                - built and reachable by direct link, but excluded from the index/feed
                          (this is the "hard to find" option for unlisted pages)

Field notes:
  - Title is the only required field.
  - Slug controls the URL. If omitted, it's auto-generated from Title.
  - Category is a single value. Tags is comma-separated and can be as many as you want.
  - Files placed directly in content/ become blog posts (articles).
  - Files in content/pages/ become standalone pages (like an About page) and never
    show up in the blog index.
-->

This is the first paragraph of the post. Standard Markdown works here: **bold**,
*italic*, `inline code`.

## A subheading

- bullet
- points

1. numbered
2. list

> A blockquote.

```python
# fenced code block, with syntax highlighting
def hello():
    return "hi"
```

[An external link](https://example.com)

Link to another post or page on this site: [see this other post]({filename}/other-post.md)

An image stored in content/images/: ![alt text]({static}/images/photo.jpg)
