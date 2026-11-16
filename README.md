# Interpol

Numerical encoding and linear and non-linear interpolation of amino acid sequences.

Compatibility updates by Renova.

Version 1.3.1.9001: `NAMESPACE` imports `splinefun` from stats, which the package calls. No other file changed.

## Install

```r
install.packages("Interpol", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/Interpol) for builds and installation. This release is tagged on GitHub as `renova-1.3.1.9001`:

```r
remotes::install_github("renova-r/Interpol@renova-1.3.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

Interpol is by Dominik Heider; the original CRAN package is at <https://CRAN.R-project.org/package=Interpol>. License: GPL (>= 2); see [COPYING](COPYING).

Original author credits: Dominik Heider, PhD, University of Duisburg-Essen, Germany

Author metadata is formatted consistently with Authors@R; original authors and maintainer roles are retained.

### Metadata compatibility

Added structured author metadata, adjusted the title and description wording, and removed the historical optional Date field.
