# Functional insights into the effect of feralisation on the gut microbiota of cats worldwide

Ostaizka Aizpurua, Amanda Bolt Botnen, Raphael Eisenhofer, Inaki Odriozola, Luisa Santos-Bay, Mads Bjorn Bjornsen, M Thomas P Gilbert, Antton Alberdi

- **DOI:** https://doi.org/10.1101/2024.09.04.611329
- **Correspondence:** antton.alberdi@sund.ku.dk, tgilbert@sund.ku.dk 

The raw code used for data analysis is in the **Rmd** files stored in the root directory of this repository, while the bookdown-rendered webbook is available at:

[alberdilab.github.io/domestic_feral_cat_metagenomics](https://alberdilab.github.io/domestic_feral_cat_metagenomics)

While the webbook provides a user-friendly overview of the procedures, analyses can be directly reproduced using the Rmd documents. Note that the code chunks that require heavy computation have been tuned off using 'eval=FALSE'. To re-render the webbook, you can use the following code:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```
