## Exploratory_Data_Analysis

This repo contains code from different books/sources. They are:

1. Exploratory Data Analysis (EDA) course at Indiana University (STAT-S 670)
2. R for Data Science code snippets
3. Data Analysis with R by Udacity

With R and RStudio installed on your local machine the packages required to run the code in this repo can be installed using the commands below in a RStudio. (Note: It is not recommended to install R using homebrew on macOS)

```{r}
my_packages <- c("tidyverse", "broom", "coefplot", "cowplot",
"gapminder", "GGally", "ggrepel", "ggridges", "gridExtra",
"here", "interplot", "margins", "maps", "mapproj",
"mapdata", "MASS", "quantreg", "rlang", "scales",
"survey", "srvyr", "viridis", "viridisLite", "devtools")

install.packages(my_packages, repos = "http://cran.rstudio.com")
```

```{r}
library('devtools')
devtools::install_github("kjhealy/socviz")
```

### Books for Reference

1. [R for Data Science](https://r4ds.had.co.nz) by Garrett Grolemund, Hadley Wickham
2. [Data Visualization: A Practical Introduction](https://socviz.co) by Kieran Healy
3. Visualizing Data by William Cleveland
