---
title: 'Post: Future Date'
date: 9999-12-31 00:00:00 Z
layout: post
categories:
- Post
last_modified_at: 2017-03-09 17:45:25 Z
---

This post lives in the future and is dated {{ page.date | date: "%c" }}. It should only appear when Jekyll builds your project with the `--future` flag.

```bash
jekyll build --future
```