
<!-- README.md is generated from README.Rmd. Please edit that file -->

# dadosBCB

<!-- badges: start -->
<!-- badges: end -->

The goal of dadosBCB is to …

## Installation

You can install the development version of dadosBCB like so:

``` r
# remotes::install_github("wilnei/dadosBCB")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(dadosBCB)
## basic example code
```

Buscando dados da série 433:

``` r
download_bcb(codigo = "433",
             data_inicial = "01-01-2022",
             data_final = "05-05-2023")
#> # A tibble: 15 × 2
#>    date       valor
#>    <date>     <dbl>
#>  1 2022-01-01  0.54
#>  2 2022-02-01  1.01
#>  3 2022-03-01  1.62
#>  4 2022-04-01  1.06
#>  5 2022-05-01  0.47
#>  6 2022-06-01  0.67
#>  7 2022-07-01 -0.68
#>  8 2022-08-01 -0.36
#>  9 2022-09-01 -0.29
#> 10 2022-10-01  0.59
#> 11 2022-11-01  0.41
#> 12 2022-12-01  0.62
#> 13 2023-01-01  0.53
#> 14 2023-02-01  0.84
#> 15 2023-03-01  0.71
```
