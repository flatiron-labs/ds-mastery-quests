# Quarto Example


Below is an R code block

``` r
library(ggplot2)

mtcars |>
    ggplot(aes(x = wt, y = mpg)) +
    geom_point() +
    labs(title = "Miles per Gallon vs Weight")
```

![](example_files/figure-commonmark/unnamed-chunk-1-1.png)

The heavier a vehicle, the worse its gas mileage!
