

### 1 - install R
* https://cran.r-project.org/

### 2 - install R studio
* https://www.rstudio.com/products/rstudio/download/

### 3 - install GSVA in R studio
* Information about GSVA: https://www.bioconductor.org/packages/release/bioc/html/GSVA.html

```
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("GSVA")
```

### 4 - install llima in R studio
* Information about llima: https://bioconductor.org/packages/release/bioc/html/limma.html

```
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("limma")
```
