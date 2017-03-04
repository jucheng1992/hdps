hdps
====

[![Build Status](https://travis-ci.org/lendle/hdps.svg)](https://travis-ci.org/lendle/hdps)

High dimensional propensity score algorithm

Note
----
This code has slgithly difference from the hdPS package in

https://github.com/lendle/hdps

In this code, the Bross formula follows:

Bross, Irwin DJ. "Spurious effects from an extraneous variable." Journal of chronic diseases 19.6 (1966): 637-647.

while the original implementation follows:

Schneeweiss, Sebastian, et al. "High-dimensional propensity score adjustment in studies of treatment effects using health care claims data." Epidemiology (Cambridge, Mass.) 20.4 (2009): 512.

Install
-------
This package can be installed using the `devtools` package in R:
```r
library(devtools)
install_github("lendle/hdps")
# or if that doesn't work, try
install_git("git@github.com:lendle/hdps")
```

Documentation
-------------

Wouldn't it be great if you could automatically generate markdown files from `.Rd` files so you could just view the docs directly on github? Well you can't. So open up R and do this instead:
```r
library(hdps)
?hdps
```



