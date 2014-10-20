Reproducible Reports
========================================================
author: Yenny Webb-Vargas
date: 10/20/2014

Reasons to use Rmd (R Markdown)
========================================================
- integrates all analyses and results, as well as written text, into one report 
- if you re-run the code in the R markdown file and (if we set the random seed and keep the original data) you get the same results

More help
========================================================

- [RStudio's R Markdown help](https://support.rstudio.com/hc/en-us/articles/200488468-R-Markdown)

Requirements for this implementation
========================================================

- R 
- RStudio
- internet connection


Steps
========================================================

- Step 0. Install the 'knitr' package (only done once)
- Step 1. Create an R markdown (Rmd) file
- Step 2. Modify the R markdown (Rmd) file
- Step 3. Knit the Rmd file into an local webpage (html) file
- Step 4. Iterate between steps 2 and 3



Step 0. Install the 'knitr' package
========================================================

```r
install.packages("knitr")
```


Step 1. Create an R Markdown (Rmd) file
========================================================

Go to the menu for new file, and select 'R Markdown'

![](menu.png)

It is good practice to create a folder for each of the R markdown projects


Step 2. Modify the R markdown (Rmd) file
========================================================