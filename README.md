## Allowing Rcpp to Interface with Custom Data Types

[![Travis-CI Build Status](https://travis-ci.org/r-pkg-examples/rcpp-custom-wrap-as.svg?branch=master)](https://travis-ci.org/r-pkg-examples/rcpp-custom-wrap-as)

The `RcppWrap` R package provides an example of creating automagic to convert
between R and C++ objects.

### Usage

To install the package, you must first have a compiler on your system that is 
compatible with R. For help on obtaining a compiler consult either
[macOS](http://thecoatlessprofessor.com/programming/r-compiler-tools-for-rcpp-on-os-x/)
or 
[Windows](http://thecoatlessprofessor.com/programming/rcpp/install-rtools-for-rcpp/)
guides.

With a compiler in hand, one can then install the package from GitHub by:

```r
# install.packages("devtools")
devtools::install_github("r-pkg-examples/rcpp-custom-wrap-as")
library("RcppWrap")
```

### Implementation Details

To do

## License

GPL (\>= 2)