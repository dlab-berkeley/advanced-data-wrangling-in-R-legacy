# D-Lab's Advanced Data Wrangling in R Workshop

This repository contains the materials for D-Lab’s Advanced Data Wrangling in R workshop. Prior experience with [Data Wrangling and Manipulation in R](https://github.com/dlab-berkeley/R-wrang) is assumed.

## Workshop Goals

The Advanced Data Wrangling Workshop aims to help students to learn powerful tools and techniques in R to wrangle data with less pain and more fun. The workshop will show how R can make your data wrangling process easier, faster, and more readable. The workshop focuses on introducing new developments in the tidyverse, particularly dplyr 1.0.0, and it has something new and exciting even for experienced R users.


First, we'll cover:

  - [Tidying and Reshaping](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/01_tidy_reshaping.Rmd)
  - [Subsetting](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/02_subsetting.Rmd)

Then, we'll explore:

  - [Summarising](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/03_summarizing.Rmd)
  - [Grouping, Nesting, and Mapping](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/04_grouping_nesting_mapping.Rmd)
  - [Joining](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R/blob/master/code/05_joining.Rmd)

Basic familiarity with data wrangling and manipulation in R is assumed. If you are not familiar with material in [Data Wrangling and Manipulation in R](https://github.com/dlab-berkeley/R-wrang), we recommend attending that workshop first. 

## Installation Instructions

We will use RStudio to go through the workshop materials, which requires installation of both the R language and the RStudio software. 

1. [Download R](https://www.r-project.org/): Follow the links according to the operating system that you are running. Download the package, and install R onto your compute. You should install the most recent version (at least version 4.0).

2. [Download RStudio](https://www.rstudio.com/products/rstudio/download/): Install RStudio Desktop. This should be free. Do this after you have already installed R.

3. Download these workshop materials:

    - Click the green "Code" button in the top right of the repository information.

    - Click "Download Zip".

    - Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

4. Optional: If you are familiar with `git`, you can instead clone this repository by opening a terminal and entering 

```
git@github.com:dlab-berkeley/advanced-data-wrangling-in-R.git
```

5. Check your `dplyr` package is up-to-date by typing `packageVersion("dplyr")` in RStudio's console. If the current installed version is less than 1.0.0, then update it by typing `update.packages("dplyr")`. You may need to restart R to make it work.

6. Install all the packages for this workshop, which are listed below in alphabetical order.

``` 
broom
estimatr
here
janitor
modelsummary
palmerpenguins 
survey
srvyr
rio
tidyverse
```

## Run the Code 

Now that you have all the required software and materials, you need to run the code: 

1. Launch the RStudio software.

2. Use the file navigator to find the `advanced-data-wrangling-in-R` folder that you downloaded. 

3. Open the `advanced-data-wrangling.Rproj` by double clicking to open the code in an R project. 

4. Open up the file corresponding to the part of the workshop currently in focus. 

5. Place your cursor on a given line and press "Command + Enter" (Mac) or "Control + Enter" (PC) to run an individual line of code. 

6. The `solutions` folder contains the solutions to the challenge problems. 

## Is R not working on your laptop? 

If you do not have R installed and the materials loaded for your workshop by the time it starts, we *strongly* recommend using the UC Berkeley DataHub to run the materials. You can access the DataHub by clicking [this link](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2Fadvanced-data-wrangling-in-R&urlpath=rstudio%2F&branch=main).

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in an RStudio instance on UC Berkeley's servers. No installation is necessary from your end--you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, go straight to [DataHub](https://datahub.berkeley.edu/), sign in, and click on the `advanced-data-wrangling-in-R` folder. 

If you do not have a Berkeley CalNet ID, you can still run these lessons in the cloud via [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/advanced-data-wrangling-in-R/master?urlpath=rstudio). If you choose to use Binder, please do so before attending the worskshop as it takes a while (especially, if you do it for the first time).

## About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

## Other D-Lab R Workshops 

Here are other R workshops offered by the D-Lab:

### Basic Competency
- [Fast-R](https://github.com/dlab-berkeley/Fast-R)
- [R Data Wrangling](https://github.com/dlab-berkeley/R-wrang)
- [R Graphics with ggplot2](https://github.com/dlab-berkeley/R-graphics)
- [R Functional Programming](https://github.com/dlab-berkeley/R-functional-programming)
- [Project Management in R](https://github.com/dlab-berkeley/efficient-reproducible-project-management-in-R)
- [Geospatial Fundamentals in R with sf](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-with-sf)
- [Census Data in R](https://github.com/dlab-berkeley/Census-Data-in-R)

### Intermediate/Advanced Competency
- [Advanced Data Wrangling in R](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R)
- [Introduction to Machine Learning in R](https://github.com/dlab-berkeley/Machine-Learning-in-R)
- [Unsupervised Learning in R](https://github.com/dlab-berkeley/Unsupervised-Learning-in-R)
- [R Machine Learning with tidymodels](https://github.com/dlab-berkeley/Machine-Learning-with-tidymodels)
- [Introduction to Deep Learning in R](https://github.com/dlab-berkeley/Deep-Learning-in-R)
- [Fairness and Bias in Machine Learning](https://github.com/dlab-berkeley/fairML)
- [R Package Development](https://github.com/dlab-berkeley/R-package-development) 

## Contributors 

- [Alex Stephenson](https://www.alexstephenson.me/) 
- [Jae Yeon Kim](https://jaeyk.github.io/)
- [Aniket Kesari](https://github.com/Akesari12)

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
