# Research compendium w/ **rrtools**

I follow the steps given at <https://github.com/benmarwick/rrtools>

* Step 1

```r
# install.packages("devtools")
devtools::install_github("benmarwick/rrtools")
```

* Step 2

Create repo `rcdummies` on GitHub, clone it via RStudio

* Step 3

```r
rrtools::use_compendium("/Users/oliviergimenez/Dropbox/OG/GITHUB/rcdummies/")
```

* Edit file DESCRIPTION

* Add package to Import via

```r
usethis::use_package("tidyverse", "imports")
```

* Add a license

```r
usethis::use_mit_license(name = "Olivier Gimenez")
```

* Generate a Readme

```r
rrtools::use_readme_rmd()
```

* Get directory for analyses

```r
rrtools::use_analysis()
```

* Work on your paper, knit the paper.Rmd

* Cool to run 

```r
rrtools::add_dependencies_to_description()
```

* Amend code of conduct and contribution (broken link to Readme)