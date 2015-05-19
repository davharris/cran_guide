# cran_guide
Recommendations for submitting an R package to CRAN

## General advice:

* Read Hadley Wickham's advice on [releasing packages](http://r-pkgs.had.co.nz/release.html), especially the section on "CRAN policies".
* Consider using Hadley Wickham's `devtools` package, especially if you're not familiar with the command line outside of R. Make sure that your package produces no warnings, errors, or notes upon running `check()`.  This runs `R CMD check` with settings that are similar to the ones CRAN uses.
* Make sure to read the following sections of the "[Writing R Extensions](http://cran.r-project.org/doc/manuals/r-release/R-exts.html)" manual:
  * [1.1 Package Structure](http://cran.r-project.org/doc/manuals/r-release/R-exts.html#DOCF2)
  * [1.1 The DESCRIPTION file](http://cran.r-project.org/doc/manuals/r-release/R-exts.html#The-DESCRIPTION-file). The "good practices" listed there, such as avoiding "this package" in the Description, are more-or-less **mandatory**.
* http://kbroman.org/pkg_primer/pages/cran.html

## For packages with compiled code

* 

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
