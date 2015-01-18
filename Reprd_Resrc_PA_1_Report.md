# Reprd_Resrc_PA_1_Report
Arrart Kongtaln  
Sunday, January 18, 2015  


## Loading and preprocessing the data

```r
activity <- read.csv("activity.csv",na.strings=c("NA",""))
##dim(activity)
##17568
##summary(activity)
steps <- c(activity$steps)
```

## What is mean total number of steps taken per day?
Histogram showing the distribution :  

```r
hist(activity$steps, breaks=50, col='blue')
```

![](Reprd_Resrc_PA_1_Report_files/figure-html/unnamed-chunk-3-1.png) 


The mean value of the total number of steps is:  

```r
mean(steps, na.rm = TRUE)
```

[1] 37.3826
#The median of the recorded number of steps is:  

```r
median(steps, na.rm = TRUE)
```

[1] 0


## What is the average daily activity pattern?



## Input the missing values



## Are there differences in activity patterns between weekdays and weekends?
