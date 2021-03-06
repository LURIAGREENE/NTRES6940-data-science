---
title: "Lesson 16: Functions Part 2 and Factors in R"
output: 
  html_document:
    keep_md: yes 
    toc: true
---
  


<br>

## Readings

<br>

#### Required: 

* [Chapters 18-21: Writing your own functions](https://stat545.com/functions-part1.html) in Jenny Bryan's STAT545 notes

* [Chapter 10: Be the boss of your factors](https://stat545.com/factors-boss.html) in Jenny Bryan's STAT545 notes


<br>

#### Other resources:

* Review the assignment for last class: [Chapter 19](https://r4ds.had.co.nz/functions.html) in R for Data Science by Hadley Wickham & Garrett Grolemund

* [Chapter 15](https://r4ds.had.co.nz/factors.html) in R for Data Science by Hadley Wickham & Garrett Grolemund

<br>

## Announcements
* The final homework is due tonight
* Wednesday is our last class - we're looking forward to your presentations

<br>

## Today's learning objectives
Today, we will first practice writing a few more functions and then we'll discuss how factors work in R.

By the end of today's class, you should be able to:

* Write a simple function to automate a task
* Describe key features of factor variables in R
* Manipulate factor levels to improve plots of categorical data

<br>
<br>

## Getting set up
We will continue working with the gapminder dataset, so let's first load that back in, along with the tidyverse.


```r
library(tidyverse)
library(gapminder) #install.packages("gapminder")

gapminder
```

<br>
<br>
