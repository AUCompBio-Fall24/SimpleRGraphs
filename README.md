
<!-- README.md is generated from README.Rmd. Please edit that file -->

SimpleRGraphs
=============

<!-- badges: start -->
<!-- badges: end -->

The goal of SimpleRGraphs is to learn base R functions that will help
visualize data in a step-wise, interactive tutorial.

Installation
------------

*If you do not have `learnr`, `devtools` and `tidyverse` installed
already, use the commented(\#) lines in the code chunks below **before**
running `library()`*

**First**: You will need `learnr` to run this tutorial (or create your
own - [learnr
documentation](https://rstudio.github.io/learnr/index.html)):

``` r
# install.packages("learnr")
library(learnr)
```

**Second**: Install the development version of the tutorial from
[GitHub](https://github.com/) with devtools:

``` r
# install.packages("devtools")
library(devtools)
devtools::install_github("adc0032/SimpleRGraphs")
```

**Third**: This tutorial package has an accompanying data package that
can be accessed from [GitHub](https://github.com/) with:

``` r
devtools::install_github("adc0032/WILD7150")
```

Running
-------

To start the tutorial, run the following command in your console:

``` r
learnr::run_tutorial("simplergraphs", package = "SimpleRGraphs")
```

Additionally, you should now have a “Tutorial” tab, where you can access
“Simple Graphs in R” by clicking **Start Tutorial** ![Tutorial
Pane](images/tutorialpane.png)
