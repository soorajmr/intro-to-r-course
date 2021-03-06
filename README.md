# An Introduction to R for Reproducible Data Analysis

This repository contains the materials used for an intro R workshop focused on exploratory analysis of tabular data. Data preparation/wrangling using `tidyverse` and data visualisation using `ggplot` are covered. The last segment of the course also covers spatial data visualisation using `sf` and `ggplot`. R markdown is used throughout to create reports and dashboards.

The presentations can be seen under the `slides` directory. The order is `basic`, `tidy`, `spatial`. The course heavily relies on the practice Rmd files in the `practice` directory. They are numbered sequentially. The practice examples initially contain simple toy data sets, but the last couple of practice sheets use tables from Census of India 2011. 

If you would like to use this materials for self learning, follow these steps:
1. **Install R**: Go to this URL and download the installer for your platform: https://cran.r-project.org/. For Windows, you can select the “base” binary. All the default options in the installation wizard should be fine. This installs the core part of the R programming language on your computer. In case you have an older version of R installed, we recommend that you still go ahead and perform this step.
2. **Install RStudio**: RStudio is the most commonly used application for creating and running R code. Download and install Rstudio desktop from here: https://rstudio.com/products/rstudio/download/#download. You could keep all the default options in the installer. 
3. **Install the required R packages**: Packages (or libraries) in R are additional optional components of the tool that we need to install. We will be making use of several packages in this course, and it will save some time if you install some of these beforehand. To do this, copy the text below and paste it at the “>” prompt in the “console” section of the Rstudio window, and press enter. On Windows, the installation should be over in a minute or two, and on Linux and Mac, it will take a little longer.
```
    install.packages(c("tidyverse", "readxl", "ggplot2", "sf", "raster", "rgdal",
                       "cartography", "zoo", "ggrepel", "gganimate", "ggridges",
                       "gifsky", "leaflet", "base64enc", "digest", "evaluate",
                       "glue", "highr", "htmltools", "jsonlite", "knitr", "magrittr",
                       "markdown", "mime", "rmarkdown", "stringi", "stringr", "tinytex",
                       "xfun", "yaml", "flexdashboard", "spdep"))
```
4. Download or clone this repository to your computer
5. Open the basic.Rmd file under the `slides` folder in RStudio. Knit it to html using the `knit` option on the menu. You should see a presentation that you can navigate slide by slide. Read the presentation.
6. When the slide contains instructions for practice, open the appropriate Rmd file in RStutio and start running the code cells one by one. You can also knit those Rmd files into html files.

Contributors:
Divij Sinha, Viola Lewis, Sooraj Raveendran
