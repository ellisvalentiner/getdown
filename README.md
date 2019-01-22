
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis build
status](https://travis-ci.org/ellisvalentiner/getdown.svg?branch=master)](https://travis-ci.org/ellisvalentiner/getdown)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/ellisvalentiner/getdown?branch=master&svg=true)](https://ci.appveyor.com/project/ellisvalentiner/getdown)
[![Coverage
status](https://codecov.io/gh/ellisvalentiner/getdown/branch/master/graph/badge.svg)](https://codecov.io/github/ellisvalentiner/getdown?branch=master)

# Overview

The downverse is a set of packages that are centered around converting R
Markdown documents into many static and dynamic output formats,
including HTML, PDF, papers, posters, presentations, and more. The
getdown package is designed to make it easy to get packages in the
downverse.

If you’d like to learn how to use the downverse effectively, the best
place to start is the [R Markdown
Gallery](https://rmarkdown.rstudio.com/gallery.html).

## Installation

getdown is not yet available on CRAN but you can install the GitHub
version:

``` r
# install.packages("pkg")
pkg::pkg_install("ellisvalentiner/getdown")
```

## Usage

`library(getdown)` will load the following packages:

  - [rmarkdown](https://github.com/rstudio/rmarkdown), for general R
    Markdown and HTML, PDF, MS Word documents and Beamer, ioslides, and
    Slidy presentations
  - [blogdown](https://github.com/rstudio/blogdown), for creating blogs
    and websites
  - [bookdown](https://github.com/rstudio/bookdown), for authoring books
    and technical documents
  - [pagedown](https://github.com/rstudio/pagedown), for creating paged
    HTML documents (resumes) for printing
  - [pkgdown](https://github.com/r-lib/pkgdown), for generating static
    html documentation for R packages
  - [posterdown](https://github.com/brentthorne/posterdown), for
    generating conference posters
  - [xaringan](https://github.com/yihui/xaringan), for creating
    slideshows with remark.js and R Markdown

However you will probably not want to load all of these packages at
once. Instead you may want to simply use getdown to install all of the
downverse packages.
