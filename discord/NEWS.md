# discord (development version)

## Bug Fixes

* Fixed error when prepping discordant data as a result of mismatched column names between user-supplied data and internally-manipulated data. See [commit fc1ed9f](https://github.com/R-Computing-Lab/discord/commit/fc1ed9f01d813cbb7f64545003bcada621a623e8) for more details.

## Minor improvements and fixes

* Added error message for missing data passed to `discord_data()` for more easy debugging.

# discord 1.1.0

## Minor improvements and fixes

* Added unit tests ensuring regression results are consistent under multiple conditions (e.g., with and without sex & race arguments)
* Removed `dplyr`, `rlang`, `purrr`, `magrittr`, `janitor`, and `broom` dependencies

# discord 1.0.0

* Added a `NEWS.md` file to track changes to the package.
* Combined the functions `kinsim1` and `kinsim_multi` into `kinsim` to simplify simulations.
* Revised `discord_data` and `discord_regression` to support functional programming and the [tidyverse](https://www.tidyverse.org/) principles.

# discord 0.1

* Initial release
