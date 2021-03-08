---
title: "{{ replace .Name "-" " " | title }}"
author: ""
type: ""
date: {{ .Date }}
subtitle: ""
image: ""
tags: []
editor_options: 
  chunk_output_type: console
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(
  comment = "#>",
  collapse = TRUE,
  cache = TRUE,
  dpi = 600,
  out.width = "100%",
  fig.align = "center",
  fig.width = 8,
  fig.asp = 0.618, # 1 / phi
  fig.show = "hold",
  dev = "png",
  message = FALSE,
  warning = FALSE,
  echo = FALSE
)

library(tidyverse)
library(ggpmthemes)

theme_set(theme_exo())
```



<details>
  
<summary>Session info</summary>

```{r sessioninfo, echo = FALSE}
## Reproducibility info
options(width = 120)
devtools::session_info()
```

</details>
