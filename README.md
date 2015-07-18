# coursera-datascience-05-RR-storms
Cousera Data Science - Reproducibale Research - Assingment-2 Storm Data

```{r}
if (file.exists("stormData.RData")) {
  load("stormData.RData")
} else {
  stormData <- read.csv("repdata_data_StormData.csv.bz2")
  save(stormData, file="stormData.RData")
}
```