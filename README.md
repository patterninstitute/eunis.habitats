
<!-- README.md is generated from README.Rmd. Please edit that file -->

# eunis.habitats <a href="https://www.pattern.institute/eunis.habitats/"><img src="man/figures/logo.svg" align="right" height="139" /></a>

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/eunis.habitats)](https://CRAN.R-project.org/package=eunis.habitats)
<!-- badges: end -->

`{eunis.habitats}` is an R data package that provides the EUNIS habitat
classification in tidy format.

Use the helper `crosswalk()` to map habitat codes across classification
systems.

## Installation

Install from CRAN:

``` r
install.packages("eunis.habitats")
```

## EUNIS classifications

The data set `eunis_habitats` provides the four EUNIS classifications:

1.  EUNIS classification from 2007, revised in 2012.
2.  EUNIS marine classification from 2019
3.  EUNIS marine classification from 2022
4.  EUNIS terrestrial classification from 2021

See `vignette("eunis-classification")` to learn more. In addition, we
also provide a helper for converting habitat codes across:

- EUNIS habitat classifications
- European Red List of Habitats
- Habitats Directive Annex I

See `vignette("crosswalks")` for more details.
