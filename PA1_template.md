# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

This document outlines the steps to analyze anonymized data collected from 
a personal activity monitoring device at 5 minute intervals for October and 
November, 2012, including the number of steps taken.

The first step is to load the data from the forked repository from [Github] (https://github.com/kpivert/RepData_PeerAssessment1). 


```r
        ## Unzip and Review File Names   
        activityData <- unzip("/Users/kpivert/RepData_PeerAssessment1/activity.zip")
        activityData ## list of files names in unzipped folder
```

```
## [1] "./activity.csv"
```

```r
        ## Read Data 
        stepData <- read.csv(activityData)
```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
