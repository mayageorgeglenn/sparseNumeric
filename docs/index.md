# sparseNumeric

`sparseNumeric` provides an S4 class for sparse numeric vectors and a
set of operations that work directly in sparse form, avoiding
materializing large dense vectors full of zeros.

## Installation

You can install the development version from GitHub:

``` r
# install.packages("remotes")
remotes::install_github("mayageorgeglenn/sparseNumeric")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r

library(sparseNumeric)

x_dense <- c(0, 0, 3, 0, -2)
y_dense <- c(1, 0, 0, 4, 0)

x <- as(x_dense, "sparse_numeric")
y <- as(y_dense, "sparse_numeric")

## Sparse arithmetic
x + y

## Sparse dot product
sparse_crossprod(x, y)

## Euclidean norm
norm(x)

## Standardization
s_std <- standardize(x)
as(s_std, "numeric")
```

## Package Website

The reference website for the package (built with pkgdown) is available
at:

<https://mayageorgeglenn.github.io/sparseNumeric/>
