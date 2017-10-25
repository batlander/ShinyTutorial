## Shiny Tutorial
A few examples to teach yourself basics of **`Shiny`** through [the tutorial](http://shiny.rstudio.com/tutorial/ "Shiny official site").

Install **`Shiny`** package as usual:

``` R
    install.packages("shiny")
    library(shiny)
```
and then run from the console the [`runUrl` function](https://shiny.rstudio.com/reference/shiny/latest/runUrl.html) :
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
>Package [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) will be installed if not present.

**Note**: These examples were done prior to version *0.10.2*, Shiny did not support single-file apps back then, and the `ui` object and `server` function needed to be contained in separate scripts called `ui.R` and `server.R`, you can find those files into the respective folders in this repository. This architecture is still supported in Shiny, so you still can run this samples as explained above.