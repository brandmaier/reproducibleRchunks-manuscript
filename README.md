

# reproducibleRchunks <img src="https://github.com/brandmaier/reproducibleRchunks/blob/main/inst/img/sticker.png" align="right" height="138" />

## What is this?

This is a research report on the purpose and functionality of the `reproducibleRchunks` package. This manuscript is currently under preparation.

## Why should I care?

The `reproducibleRchunks` package allows you to make computational results in R testable for reproduction (does the same script with the same data produce the same results, e.g. on a different computer and/or later in time). There is only a single thing you need to change in your analysis if you are already using RMarkdown: Load the package at the beginning of your R Markdown file (`library(reproducibleRchunks)`) and change the code chunk type from `r` to `reproducibleR`. It's that easy:

![](inst/img/rstudio-screenshot-marker2.png)