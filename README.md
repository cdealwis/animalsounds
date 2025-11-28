
<!-- README.md is generated from README.Rmd. Please edit that file -->

# animalsounds

<!-- badges: start -->

<!-- badges: end -->

The goal of animalsounds is to help users to mix animals and sounds like
you want. The cow should go woof? No problem for animalsounds!

## Installation

You can install the development version of animalsounds from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("cdealwis/animalsounds")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(animalsounds)
## basic example code
animal_sounds("dog", "woof") 
#> [1] "The dog goes woof!"
animal_sounds("cow", "miaow")
#> [1] "The cow goes miaow!"
```
