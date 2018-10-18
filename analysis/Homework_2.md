Homework 2
================

``` r
library(tidyverse)
```

    ## -- Attaching packages ----------------------------------------------------------------------------------------------------------- tidyverse 1.2.1 --

    ## v ggplot2 3.0.0     v purrr   0.2.5
    ## v tibble  1.4.2     v dplyr   0.7.6
    ## v tidyr   0.8.1     v stringr 1.3.1
    ## v readr   1.1.1     v forcats 0.3.0

    ## -- Conflicts -------------------------------------------------------------------------------------------------------------- tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
data <- read_tsv("../data/example_dataset_2.tsv") %>% print()
```

    ## Parsed with column specification:
    ## cols(
    ##   strain = col_character(),
    ##   mean_yfp = col_integer(),
    ##   mean_rfp = col_integer()
    ## )

    ## # A tibble: 16 x 3
    ##    strain  mean_yfp mean_rfp
    ##    <chr>      <int>    <int>
    ##  1 schp688     1748    20754
    ##  2 schp684     3294    20585
    ##  3 schp690     3535    20593
    ##  4 schp687     4658    20860
    ##  5 schp686     5000    21171
    ##  6 schp685     7379    22956
    ##  7 schp683     9365    23866
    ##  8 schp689     8693    22649
    ##  9 schp679     2528    19906
    ## 10 schp675     3687    20438
    ## 11 schp681     3705    20227
    ## 12 schp678     4378    20630
    ## 13 schp677     3967    20604
    ## 14 schp676     2657    20223
    ## 15 schp674     1270    20316
    ## 16 schp680     1117    19377

\`\`\`\`
