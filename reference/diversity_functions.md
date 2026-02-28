# Diversity Index Functions

These are core low-level routines for the computation of multiple
diversity indices, designed to be used by
[`diversity.calc`](https://aravind-j.github.io/DiversityStats/reference/diversity.calc.md)
and other functions.

## Usage

``` r
berger_parker(x)

berger_parker_reciprocal(x)

simpson(x)

gini_simpson(x)

simpson_max(x)

simpson_reciprocal(x)

simpson_relative(x)

simpson_evenness(x)

shannon(x, base = 2)

shannon_max(x, base = 2)

shannon_relative(x, base = 2)

shannon_ens(x, base = 2)

mcintosh_diversity(x)

mcintosh_evenness(x)

smith_wilson(x, warn = TRUE)

heip_evenness(x)

margalef_index(x)

menhinick_index(x)

brillouin_index(x)

hill_number(x, q = 1)

renyi_entropy(x, q = 1)

tsallis_entropy(x, q = 1)

hill_evenness(x, q = 1)
```

## Arguments

- x:

  A factor vector of categories (e.g., species, traits). The frequency
  of each level is treated as the abundance of that category.

- base:

  The logarithm base to be used for computation of shannon family of
  diversity indices. Default is `exp(1)`.

- warn:

  logical. If `TRUE` shows the relevant warning. Default is `TRUE`.

- q:

  The order of the parametric index.

## Value

The calculated diversity index value.
