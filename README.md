[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/advanced-data-wrangling-in-R/master?urlpath=rstudio)

# Advanced Data Wrangling Workshop in R

by [Jae Yeon Kim](https://jaeyk.github.io/)

File an [issue](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/issues) if you have problems, questions or suggestions.

## Overview

The Advanced Data Wrangling Workshop aims to help students to learn powerful tools and techniques in R to wrangle data with less pain and more fun. The workshop will show how R can make your data wrangling process easier, faster, and more readable. The workshop focuses on introducing new developments in the tidyverse, particularly dplyr 1.0.0, and it has something new and exciting even for experienced R users.

## Learning objectives

- Part 1: Learn how to reshape and manipulate data

  - [Tidying and Reshaping](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/01_tidy_reshaping.Rmd)
  - [Subsetting](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/02_subsetting.Rmd)

- Part 2: Learn how to summarize data using the tidyverse packages

  - [Summarising](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/03_summarizing.Rmd)
  - [Grouping, Nesting, and Mapping](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/04_grouping_nesting_mapping.Rmd)
  - [Joining](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/05_joining.Rmd)

## Setup

I strongly recommend to launch the binder above. Please do so before attending the worskshop as it takes a while (especially, if you do it for the first time).

Or you can setup manually:

- Check your `dplyr` package is up-to-date by typing `packageVersion("dplyr")`.
- If the current installed version is less than 1.0.0, then update it by typing `update.packages("dplyr")`. You may need to restart R to make it work.

```{r}

ifelse(packageVersion("dplyr") > 1, 
  print("The installed version of dplyr package is greater than or equal to 1.0.0"), 
  update.packages("dplyr")
  )

```

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
