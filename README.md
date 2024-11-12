
<!-- README.md is generated from README.Rmd. Please edit that file -->

# SimpleRGraphs

<!-- badges: start -->
<!-- badges: end -->

The goal of SimpleRGraphs is to learn base R functions that will help
visualize data in a step-wise, interactive tutorial.

## BIOL 5800/6800 Students

Once complete, this tutorial should address the **following learning
objectives**:

-   Learn to create different graphs using basic R functions
    -   Line Graphs
    -   Bar Graphs
    -   Pie Graphs
    -   Histograms
    -   Dot Graphs
-   Learn to manipulate and customize graphs created with base R
-   Apply rendering methods from video lectures to create a PDF of
    graphs

## Installation

#### Linking your Github and Rstudio

This tutorial was built in and works within Rstudio but it also works in
web browsers. The packages developed for this tutorial are hosted on
Github, so you will need to install some packages to get it to work locally.

#### Programs to download outside of Rstudio

Note: the following softwares ONLY need to be installed if you get an error when trying to install the code in the next step: 

**Mac Users** may need [Xcode developer tools from the App
store](https://developer.apple.com/xcode/features/) in order to use
`devtools`  
**Windows Users** may need [Rtools from
CRAN](https://cran.r-project.org/bin/windows/Rtools/) in order to use
`devtools`

#### Now install the tutorial!

*If you do not have `learnr` & `devtools` installed already, use the
commented(#) lines in the code chunks below **before** running
`library()`*

**First**: You will need `learnr` to run this tutorial (or create your
own - [learnr
documentation](https://rstudio.github.io/learnr/index.html)):

``` r
# Run the install line ONCE
install.packages("learnr")

library(learnr)
```

**Second**: Install the development version of the tutorial from
[GitHub](https://github.com/) with devtools:

``` r
# Run the install line ONCE and then comment it out afterwards
install.packages("devtools")

library(devtools)
# Run the install line ONCE and then comment it out afterwards
devtools::install_github("adc0032/SimpleRGraphs")
```

**Third**: This tutorial package has an accompanying data package that
can be accessed from [GitHub](https://github.com/) with:

``` r
# Run the install line ONCE and then comment it out afterwards
devtools::install_github("adc0032/WILD7150")
```

The package also requires `tidyverse`, but you should be prompted to
install if you do not have it installed already.

``` r
# Run the install line ONCE and then comment it out afterwards
install.packages("tidyverse")

library(tidyverse)
```

## Running

To start the tutorial **in a web browser (pref. Google Chrome)**, run
the following command in your console:

``` r
learnr::run_tutorial("simplergraphs", package = "SimpleRGraphs")
```

Additionally, you should now have a “Tutorial” tab, where you can access
“Simple Graphs in R” by clicking **Start Tutorial** This will start the
tutorial **in an Rstudio window** ![Tutorial
Pane](images/tutorialpane.png)
