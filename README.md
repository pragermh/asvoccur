# asvoccur
Tools for ASV occurrence data in SBDI

## Install
```R
# install.packages('devtools')
# install.packages('data.table')
library(devtools)
install_github("pragermh/asvoccur")
library(data.table)
library(asvoccur)
```
## Run
```R
data_path <- '/path-to/dataset-folder'
loaded <- load_data(data_path)
merged <- merge_data(loaded)
```

## Get help
```R
?asvoccur::load_data
?asvoccur::merge_data
```
