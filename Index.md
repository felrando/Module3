---
title: "Module3HTMLDoc"
author: "UrMom"
date: "2024-10-23"
output: 
  html_document:
    keep_md: true
    fig_width: 5
    fig_height: 5
    toc: yes
    toc_float: true
    code_folding: hide
    #css: mycss.css
    #theme: yeti
    #highlight: espresso
---



# UrMom

## R Markdown {#nextsteps .emphasized}

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

### Plot of the Cars Dataset


```r
#summary(cars)
plot(cars)
```

![](Index_files/figure-html/cars-1.png)<!-- -->

## Including Plots

You can also embed plots, for example:

### Plot of the Pressure Dataset

![](Index_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## A list

* a
* b
* c

## An equation

$$ Y = X^2 + \beta_0/3 $$
