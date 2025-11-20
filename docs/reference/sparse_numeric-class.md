# Sparse numeric vector class

An S4 class to represent numeric vectors in sparse form.

## Slots

- `value`:

  Numeric vector of non-zero values.

- `pos`:

  Integer vector of positions (1-based) of non-zero values.

- `length`:

  Integer giving the total length of the vector (including zeros).
