# AlwaysMap Website

## Author an article

Create the new file and run the local hugo server to preview and you work:

```sh
hugo new post/my-article.md
hugo server -D
```

Update front matter for the new article.

```yaml
---
date: '2025-12-09T23:10:10-07:00'
draft: true
title: Why AlwaysMap?
author: Dylan
summary: |-
  The conversations and needs led us to the AlwaysMap idea.
---
```

Write content using Markdown.
Install Hugo:

## Publish

Change the `draft: false` to `draft: true` in the front matter when you are ready to publish.
Then use typical `git` commands:


```sh
git add .
git commit -m "Add new article"
git push
```

This will trigger the GitHub Actions workflow to deploy the updated website.
