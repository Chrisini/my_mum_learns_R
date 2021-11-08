

### 1 - install R: https://cran.r-project.org/

### 2 - install R studio: https://www.rstudio.com/products/rstudio/download/

### 3 - install GSVA in R studio
https://www.bioconductor.org/packages/release/bioc/html/GSVA.html

```javascript
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
```
```javascript
BiocManager::install("GSVA")
```
outcome: installation of package ‘glue’ had non-zero exit status

### 4 - install llima in R studio
https://bioconductor.org/packages/release/bioc/html/limma.html

```javascript
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
```

```javascript
BiocManager::install("limma")
```
