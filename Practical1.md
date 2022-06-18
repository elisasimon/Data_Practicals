Practical 1 - Data Science
================
Elisa Simon
11 06 2022

# Hair and eye color

In their articles *The Genetic Overlap Between Hair and Eye Color*, Lin
et al. (2016) examined the correlation between eye and hair color of
Netherlands people. They found multiple correlations but it is worth
mentioning two:

-   The **strongest** genetic correlation was between blue eyes and
    blond hair.

-   The **weakest** genetic correlation was between green eyes and red
    hair.

The ggplot2 package is very useful to visualize data. One can install it
as following:

``` r
install.packages("ggplot2")
library(ggplot2)
```

Unfortunately, Lin et al. (2016) are not open-scientists and I failed to
find their original data. Consequently, I am not able to reproduce any
graph. Consolation prize: a picture of a blond haired-blue eyed doll.

![](https://i.etsystatic.com/9003800/d/il/d98430/2444030466/il_340x270.2444030466_pmac.jpg?version=0)

## HairEyeColor R built-in data

There is a pre-loaded dataset in R about hair and eye color that one can
get like this:

``` r
# Table: hair and eye color for males and females
data(HairEyeColor)
HairEyeColor
```

    ## , , Sex = Male
    ## 
    ##        Eye
    ## Hair    Brown Blue Hazel Green
    ##   Black    32   11    10     3
    ##   Brown    53   50    25    15
    ##   Red      10   10     7     7
    ##   Blond     3   30     5     8
    ## 
    ## , , Sex = Female
    ## 
    ##        Eye
    ## Hair    Brown Blue Hazel Green
    ##   Black    36    9     5     2
    ##   Brown    66   34    29    14
    ##   Red      16    7     7     7
    ##   Blond     4   64     5     8

In this sample, we can see that the blond hair blue eyes combination is
only the most represented in female people. Additionally, there is no
evidence in this sample that the rarest combination is red hair and
green eyes, neither in males nor in females.

# References

<div iv="refs">

</div>

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-lin_genetic_2016" class="csl-entry">

Lin, Bochao D., Gonneke Willemsen, Abdel Abdellaoui, Meike Bartels, Erik
A. Ehli, Gareth E. Davies, Dorret I. Boomsma, and Jouke J. Hottenga.
2016. “The Genetic Overlap Between Hair and Eye Color.” *Twin Research
and Human Genetics* 19 (6): 595–99.
<https://doi.org/10.1017/thg.2016.85>.

</div>

</div>
