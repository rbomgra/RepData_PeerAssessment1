# Reproducible Research: Peer Assessment 1
========================================================



## Loading and preprocessing the data
Step 1: Read the data: 


```r
setInternet2(TRUE)
fileUrl <- "https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip"
download.file(fileUrl, destfile="repdata_Fdata_Factivity.zip", method="auto")
Factivity <- read.csv(unz("repdata_Fdata_Factivity.zip","activity.csv"))
unlink("activity.csv")
```

Date file download: 

```r
date
```

```
## [1] "Thu Jun 12 08:15:40 2014"
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values


## Are there differences in activity patterns between weekdays and weekends?
