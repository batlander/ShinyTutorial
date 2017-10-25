# Readme

## Shiny Tutorial
A few examples to teach yourself basics of **`Shiny`** through [the tutorial](http://shiny.rstudio.com/tutorial/ "Shiny official site")

Install **`Shiny`** package as usual:

``` R
    install.packages("shiny")
    library(shiny)
```
and then run from the console:
``` R
    runGitHub("ShinyTutorial", "joanh", subdir = "HelloShiny")
```
``` R
    runGitHub("ShinyTutorial", "joanh", subdir = "ShinyText")
```
``` R
    runGitHub("ShinyTutorial", "joanh", subdir = "Census-app")
```
>Packages [maps](https://cran.r-project.org/web/packages/maps/index.html) and [mapproj](https://cran.r-project.org/web/packages/mapproj/index.html) will be installed if not present.

``` R
    runGitHub("ShinyTutorial", "joanh", subdir = "StockVis")
```
>Package [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) will be installed if not present