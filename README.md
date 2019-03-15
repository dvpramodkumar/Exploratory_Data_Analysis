## Exploratory_Data_Analysis

This repo contains code from the Exploratory Data Analysis course at Indiana University (STAT-S 670)

```{R Code}
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

### Books for Reference:

1. [R for Data Science](https://r4ds.had.co.nz) by Garrett Grolemund, Hadley Wickham
2. [Data Visualization: A Practical Introduction](https://socviz.co) by Kieran Healy
3. Visualizing Data by William Cleveland
