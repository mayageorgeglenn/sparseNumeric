# Standardize a sparse_numeric vector

Standardizes each element of a `sparse_numeric` vector by subtracting
the mean and dividing by the standard deviation (as in
[`sd()`](https://rdrr.io/r/stats/sd.html)).

## Usage

``` r
standardize(x, ...)

# S4 method for class 'sparse_numeric'
standardize(x, ...)
```

## Arguments

- x:

  A `sparse_numeric` vector.

- ...:

  Ignored.

## Value

A standardized `sparse_numeric` vector.
