---
title: "Test"
date: 2021-08-21T08:42:29+10:00
draft: true
---

```{r}
library(fitzRoy)

paste("Hello", "World")

afltables %>%
    select(id, first_name, surname) %>%
    View()

```

| Rank | Table Header | Second Header | Third Header             |
| :--- | :----------- | ------------: | -----------------------: |
| 1    | *Cell one*   | **Cell two**  | The quick brown fox      |
| 2    | `Cell 3`     | ~~Cell 4~~    | jumped over the lazy dog |

*[Note:](https://somethingpositive.net/)*

endash: --

emdash: ---

ellipsis: ...