---
editor_options: 
  markdown: 
    wrap: 72
---

# masstools <img src="man/figures/logo.png" align="right" width="120"/>

[![](https://www.r-pkg.org/badges/version/masstools?color=green)](https://cran.r-project.org/package=masstools)
[![](https://img.shields.io/github/languages/code-size/tidymass/masstools.svg)](https://github.com/tidymass/masstools)
[![Dependencies](https://tinyverse.netlify.com/badge/masstools)](https://cran.r-project.org/package=masstools)
[![](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

`masstools` is a part of [tidymass](https://www.tidymass.org/)

------------------------------------------------------------------------

## About

`masstools` is a collections of useful tiny tools for mass spectrometry
data processing.

## Installation

### Bioconductor (recommended)

`masstools` is distributed via Bioconductor. Installing from
Bioconductor ensures tested binaries (where available), pinned
dependencies, and better reproducibility.

``` r
# 1) Install BiocManager if needed
if (!requireNamespace("BiocManager", quietly = TRUE))
  install.packages("BiocManager")

# 2) Install the latest *release* version of masstools
BiocManager::install("masstools")
```

#### Install the *devel* version (for developers/testers)

If you specifically need the development branch of Bioconductor:

``` r
# Switch your R session to Bioconductor devel and then install
BiocManager::install(version = "devel")
BiocManager::install("masstools")
```

### GitHub (not recommended for end users)

A development snapshot is also available on GitHub:

``` r
# Choose one of the following if you understand the trade-offs:
# remotes::install_github("tidymass/masstools")
# pak::pkg_install("github::tidymass/masstools")
devtools::install_github("tidymass/masstools")
```

> **Important:** Installing from GitHub is primarily for contributors
> and early testing. It bypasses Bioconductor’s release/devel channels
> and may skip platform-tested binaries and version-pinned dependencies,
> which can reduce reproducibility and stability. For most users,
> **installing from Bioconductor (release or devel) is strongly
> recommended.**

## Usage

Please see the `Help documents` page to get the instruction of
`masstools`.

## Need help?

If you have any questions about `masstools`, please don’t hesitate to
email me ([shenxt\@stanford.edu](mailto:shenxt@stanford.edu){.email}) or
reach out me via the social medias below.

<i class="fa fa-weixin"></i>
[shenxt1990](https://www.shenxt.info/files/wechat_QR.jpg)

<i class="fa fa-envelope"></i>
[shenxt\@stanford.edu](mailto:shenxt@stanford.edu){.email}

<i class="fa fa-twitter"></i>
[Twitter](https://twitter.com/JasperShen1990)

<i class="fa fa-map-marker-alt"></i> [M339, Alway Buidling, Cooper Lane,
Palo Alto, CA
94304](https://www.google.com/maps/place/Alway+Building/@37.4322345,-122.1770883,17z/data=!3m1!4b1!4m5!3m4!1s0x808fa4d335c3be37:0x9057931f3b312c29!8m2!3d37.4322345!4d-122.1748996)

## Citation

If you use `masstools` in your publications, please cite this paper:

Shen, X., Yan, H., Wang, C. et al. TidyMass an object-oriented
reproducible analysis framework for LC–MS data. Nat Commun 13, 4365
(2022).

[Weblink](https://www.nature.com/articles/s41467-022-32155-w)

Thanks very much!
