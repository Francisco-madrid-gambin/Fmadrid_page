---
date: "`r Sys.Date()`"
title: working on this page
---



When creating a new post, you have to decide whether the post format is Markdown or R Markdown, and this can be done via the `ext` argument of the function `blogdown::new_post()`, e.g.

```r
blogdown::new_post("Post Title", ext = '.Rmd')
```
