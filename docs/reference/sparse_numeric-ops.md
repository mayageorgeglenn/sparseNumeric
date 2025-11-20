# Arithmetic operators for sparse_numeric vectors

These methods allow you to use the standard arithmetic operators `+`,
`-`, and `*` with `sparse_numeric` vectors. They dispatch to
[`sparse_add()`](sparse_add.md), [`sparse_sub()`](sparse_sub.md), and
[`sparse_mult()`](sparse_mult.md) respectively.

## Usage

``` r
# S4 method for class 'sparse_numeric,sparse_numeric'
e1 + e2

# S4 method for class 'sparse_numeric,sparse_numeric'
e1 - e2

# S4 method for class 'sparse_numeric,sparse_numeric'
e1 * e2
```

## Arguments

- e1, e2:

  Objects of class `sparse_numeric`.
