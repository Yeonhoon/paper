---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
description: ""
date: {{ .Date }}
author: "JYH"
output:
  html_document:
    fig_height: 5
    fig_width: 10
    highlight: textmate
    theme: cosmo
    toc: yes
    toc_depth: 3
    toc_float: yes
imgs: []
cover: ""  # image show on top
readingTime: true  # show reading time after article date
comments: True
justify: false  # text-align: justify;
single: false  # display as a single page, hide navigation on bottom, like as about page.
license: ""  # CC License

---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo=F, fig.align = "center", message=F, warning=F, fig.height = 5, fig.widget = 5, cache=T, dpi = 300)
```
