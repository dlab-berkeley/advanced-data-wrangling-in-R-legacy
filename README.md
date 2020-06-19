[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jaeyk/advanced-data-wrangling/master)

# Advanced Data Wrangling Workshop in R

by [Jae Yeon Kim](https://jaeyk.github.io/)

## Overview

The Advanced Data Wrangling Workshop aims to help students to learn powerful data wrangling tools and techniques in R to wrangle data with less pain and more fun. The workshop will show how R can make your data wrangling process faster, more reliable, and interpretable. The workshop focuses on introducing new package developments in the tidyverse, particularly dplyr 1.0.0, and it has something new and exciting even for experienced R users.

## Learning objectives

- Part 1: Learn how to reshape and manipulate data

  - [Tidying and Reshaping](https://github.com/jaeyk/advanced-data-wrangling/blob/master/code/01_tidy_reshaping.Rmd)
  - [Subsetting](https://github.com/jaeyk/advanced-data-wrangling/blob/master/code/02_subsetting.Rmd)

- Part 2: Learn how to summarize data using the tidyverse packages

  - [Summarising](https://github.com/jaeyk/advanced-data-wrangling/blob/master/code/03_summarizing.Rmd)
  - [Grouping and Nesting](https://github.com/jaeyk/advanced-data-wrangling/blob/master/code/04_grouping_nesting.Rmd)
  - [Joining](https://github.com/jaeyk/advanced-data-wrangling/blob/master/code/05_joining.Rmd)

## Setup
- `pacman` is a great package management tool in R. (For more information, see [the package vignette](http://trinker.github.io/pacman/vignettes/Introduction_to_pacman.html).)

- Check your `dplyr` package is up-to-date by typing `packageVersion("dplyr")`. If the current installed version is less than 1.0.0, then update it by typing `update.packages("dplyr")`. You may need to restart R to make it work.

``` r

# p_load loads and, if necessary, install missing packages.
# install.packages() + library() = p_load()
# If you just want to install, then use p_install()

if (!require("pacman")) install.packages("pacman")
pacman::p_load(
  tidyverse, # for the tidyverse framework
  here # for computational reproducibility
  )

```

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
