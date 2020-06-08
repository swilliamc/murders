Report on Gun Murders
================
S William Chan
6/7/2020

## Introduction

This is a report on 2010 gun murder rates obtained from FBI reports. The
original data was obtained from this Wikipedia page. We are going to use
the following library:

``` r
library(tidyverse)
```

    ## -- Attaching packages ------------------ tidyverse 1.3.0 --

    ## v ggplot2 3.3.0     v purrr   0.3.4
    ## v tibble  3.0.0     v dplyr   0.8.5
    ## v tidyr   1.0.2     v stringr 1.4.0
    ## v readr   1.3.1     v forcats 0.5.0

    ## -- Conflicts --------------------- tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

and load the data we already wrangled:

``` r
load("rda/murders.rda")
```

## Murder rate by state

We note the large state to state variability by generating a barplot
showing the murder rate by state:

![](Report_files/figure-gfm/murder-rate-by-state-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
