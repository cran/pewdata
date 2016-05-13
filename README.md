[![CRAN version](http://www.r-pkg.org/badges/version/pewdata)](https://cran.r-project.org/package=pewdata) ![](http://cranlogs.r-pkg.org/badges/grand-total/pewdata) [![Travis-CI Build Status](https://travis-ci.org/fsolt/pewdata.svg?branch=master)](https://travis-ci.org/fsolt/pewdata)
------------------------------------------------------------------------
pewdata
=========

`pewdata` is an R package that provides reproducible, programmatic access to survey datasets from the [Pew Research Center](http://www.pewresearch.org).

`pewdata` is not yet on CRAN.  To install the latest development version: 

```R
if (!require(ghit)) install.packages("ghit")
ghit::install_github("fsolt/pewdata")
```
Note that `pewdata` depends on the Firefox browser; if you don't already have it installed on your machine, [get it here](https://www.mozilla.org/firefox).

For more details, check out [the vignette](https://github.com/fsolt/pewdata/blob/master/vignettes/pewdata-vignette.Rmd).
