Generate with Pandoc
====================

Pandoc sample
-------------

``` {.r}
% Pandoc command line (from presentation directory)
pandoc -t revealjs -s -o pandoc_pres.html pandoc_pres.md _pres.yaml -V revealjs-url=./reveal.js-3.6.0
```

In the morning
==============

Getting up
----------

-   Turn off alarm
-   Get out of bed

Breakfast {#breakfast data-background="#dddddd"}
---------

-   Eat eggs
-   Drink coffee

In the evening
==============

Dinner
------

-   Eat spaghetti
-   Drink wine

Going to sleep
--------------

-   Get in bed
-   Count sheep

Inclusion of R code
===================

R Markdown
----------

This is an R Markdown presentation. Markdown is a simple formatting
syntax for authoring HTML, PDF, and MS Word documents. For more details
on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document.

Slide with R Output
-------------------

``` {.r}
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Slide with Plot
---------------

![](pandoc_pres_files/figure-markdown/pressure-1.png)
