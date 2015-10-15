# Reproducible Research: Peer Assessment 1
Flavius Popan  
October 15, 2015  


## Loading and preprocessing the data

```r
## Extract the csv from the zip if it hasn't been done already
if (!file.exists("activity.csv")) {unzip("activity.zip")}

## Load the csv file as a dataset
activity <- read.csv("activity.csv")
```


## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?

