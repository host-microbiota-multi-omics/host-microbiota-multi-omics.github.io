# Host-microbiota multi-omics

Main repository of the computational exercises of the course

[host-microbiota-multi-omics.github.io](https://host-microbiota-multi-omics.github.io)

## Render webook

The webbook has been rendered using the following script:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```

