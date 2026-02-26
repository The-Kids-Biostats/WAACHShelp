# WAACHShelp

[![name status
badge](https://the-kids-biostats.r-universe.dev/badges/:name)](https://the-kids-biostats.r-universe.dev/)
[![WAACHShelp status
badge](https://the-kids-biostats.r-universe.dev/WAACHShelp/badges/version)](https://the-kids-biostats.r-universe.dev/WAACHShelp)
![R-CMD-check](https://github.com/The-Kids-Biostats/WAACHShelp/actions/workflows/R-CMD-check.yaml/badge.svg)[![Codecov
test
coverage](https://codecov.io/gh/The-Kids-Biostats/WAACHShelp/graph/badge.svg)](https://app.codecov.io/gh/The-Kids-Biostats/WAACHShelp)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![DOI](https://zenodo.org/badge/849158197.svg)](https://doi.org/10.5281/zenodo.17460007)

General helper functions for the WAACHS linked data project.

## Installation instructions

The package can be installed from the R-universe, by:

    install.packages("WAACHShelp", repos = "https://the-kids-biostats.r-universe.dev")

Alternatively, the package can be installed using `remotes`:

    remotes::install_github(repo = "The-Kids-Biostats/WAACHShelp", build_vignettes = TRUE)

## Accessing vignettes

Vignettes have been built for some of the functions. These can be opened
in R or via the [package
website](https://the-kids-biostats.github.io/WAACHShelp/). The vignettes
have the same name as the function.

At the moment, vignettes exist for:

- `icd_morb_flag`
- `create_project`
- `create_markdown`
- `aducust_flag`

Accessing these vignettes can be done two ways:

1.  Using `utils::browseVignettes(package = "WAACHShelp")`
    - Opens vignette via web browser.
2.  Using `vignette(x, package = "WAACHShelp")` where x is the function
    name
    - Opens the vignette in the “Help” tab of RStudio.
