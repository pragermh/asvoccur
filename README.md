# asvoccur
Tools for ASV occurrence data in SBDI

## Install
```R
install.packages('devtools')
library(devtools)
install_github("pragermh/asvoccur")
# or:
# install_github("pragermh/asvoccur@develop")
library(asvoccur)

```
## Run
```R
data_path <- '/path-to/dataset-folder'
loaded <- load_data(data_path)
merged <- merge_data(loaded)
summed <- sum_by_clade(merged$counts, merged$asvs)
summed_df <- convert_to_df(summed)
```

## Get help
```R
?asvoccur::load_data
?asvoccur::merge_data
?asvoccur::sum_by_clade
?asvoccur::convert_to_df
```
