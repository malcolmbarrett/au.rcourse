
<!-- README.md is generated from README.Rmd. Please edit that file -->

# au.rcourse

<!-- badges: start -->
<!-- badges: end -->

You can install au.rcourse from this repository with

``` r
options(repos = 'https://packagemanager.rstudio.com/all/latest')
install.packages("remotes")
remotes::install_github("malcolmbarrett/au.rcourse")
```

`au.rcourse::use_module()` will install the materials for a given module
on your computer. Then, it will open a new RStudio Project containing
the files you’ll need.

``` r
au.rcourse::use_module("module_name")
```

By default, this package downloads the materials to a conspicous place
like your Desktop. You can also tell `use_module()` exactly where to put
the materials with `destdir`:

``` r
au.rcourse::use_module("module_name", destdir = "a/path/on/your/computer")
```
