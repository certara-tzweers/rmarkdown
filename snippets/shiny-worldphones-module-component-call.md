---
title: "World Phones"
output: html_document
runtime: shiny_prerendered
---

```{r, context="setup", include=FALSE}
source("worldPhones.R")
```

```{r, echo=FALSE}
worldPhones("phones", selected = "Asia",  height = 500)
```