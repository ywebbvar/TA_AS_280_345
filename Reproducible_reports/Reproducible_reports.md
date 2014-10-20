Reproducible Reports
========================================================
author: Yenny Webb-Vargas
date: 10/20/2014

Reasons to use Rmd (R Markdown)
========================================================
- integrates all analyses and results, as well as written text, into one report 
- reproducibility. If you re-run the code in the R markdown file and (if we set the random seed and keep the original data) you get the same results


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

It is good practice to create a folder for each of the R markdown projects.


Step 2. Modify the R markdown (Rmd) file
========================================================

- Title (title, author, date)
- Text
- 'Chunks' that contain R code


Step 3. Knit the Rmd file into an output file (html, pdf or doc)
=========================================================

- R markdown document is saved with the extension Rmd
- this document is then 'knitted' by the 'knitr' package into a markdown file, 
- the markdown file is converted to an output file (MS Word). 

RStudio does all of these for us when we press 'Knit Word'.


Step 3. Knit the Rmd file into an output file (html, pdf or doc)
=========================================================

The final product of an R markdown file is an output file that contains: 
- text, with headings
- R code with color highlights
- R output
- Figures


Step 4. Iterate between steps 2 and 3
=========================================================

Write text, insert chunks, write math, show R output, plot, integrate R results within the text


Further learning:
========================================================

- [RStudio's R Markdown help](https://support.rstudio.com/hc/en-us/articles/200488468-R-Markdown)
