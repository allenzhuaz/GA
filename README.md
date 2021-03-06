
<!-- README.md is generated from README.Rmd. Please edit that file -->
GA <img src="inst/sticker.png" align="right" width="120px" />
=============================================================

[![CRAN\_Status](http://www.r-pkg.org/badges/version/GA)](https://cran.r-project.org/package=GA) [![CRAN\_MonthlyDownloads](http://cranlogs.r-pkg.org/badges/GA)](https://cran.r-project.org/package=GA) [![Rdoc](http://www.rdocumentation.org/badges/version/GA)](http://www.rdocumentation.org/packages/GA)

An R package for optimization using **genetic algorithms**. The package provides a flexible general-purpose set of tools for implementing genetic algorithms search in both the continuous and discrete case, whether constrained or not. Users can easily define their own objective function depending on the problem at hand. Several genetic operators are available and can be combined to explore the best settings for the current task. Furthermore, users can define new genetic operators and easily evaluate their performances. Local search using general-purpose optimisation algorithms can be applied stochastically to exploit interesting regions. GAs can be run sequentially or in parallel, using an explicit master-slave parallelisation or a coarse-grain islands approach.

Installation
------------

Get the released version from CRAN:

``` r
install.packages("GA")
```

Or the development version from GitHub:

``` r
# install.packages("devtools")
devtools::install_github("luca-scr/GA")
```

Usage
-----

See the papers in the references section below. A quick intro vignette is also available, which can be accessed using

``` r
vignette("GA")
```

Note that if the package is installed from GitHub the vignette is not automatically created. However, it can be created when installing from GitHub with the code:

``` r
devtools::install_github("luca-scr/GA", build_vignettes = TRUE)
```

References:
-----------

Scrucca, L. (2013) GA: A Package for Genetic Algorithms in R. **Journal of Statistical Software**, 53(4), 1-37. <https://www.jstatsoft.org/article/view/v053i04>

Scrucca, L. (2017) On some extensions to GA package: hybrid optimisation, parallelisation and islands evolution. **The R Journal**, 9/1, 187–206. <https://journal.r-project.org/archive/2017/RJ-2017-008>
