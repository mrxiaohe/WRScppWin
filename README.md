WRScppWin
=========

This is a Windows binary of the `C++` sub-routines for the `R` package `WRS` for robust statistic methods.

###[Installation]

####To install this package, four R packages are required:

* `WRS`
* `RcppArmadillo` and `Rcpp`: These two packages allow convenient interface between R and C++. `RcppArmadillo` requires `Rcpp`, so installing the first one will automatically prompt R to install the latter.
* `devtools`: This package allows R users to install packages hosted on Github.

        install.packages("WRS", repos="http://R-Forge.R-project.org", type="source")
        install.packages( c("RcppArmadillo", "devtools") )

####Next, load devtools and install the WRScpp binary:

    library("devtools")
    install_github(repo="WRScppWin", username="mrxiaohe")  



##For the Mac binary and examples, go to this link: (https://github.com/mrxiaohe/WRScpp)
