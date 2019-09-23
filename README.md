[![Build Status](https://travis-ci.org/erocoar/bundestag.svg?branch=master)](https://travis-ci.org/erocoar/bundestag)
[![CRAN_Release_Badge](http://www.r-pkg.org/badges/version-ago/bundestag)](https://CRAN.R-project.org/package=bundestag)
[![CRAN_Download_Badge](http://cranlogs.r-pkg.org/badges/grand-total/bundestag)](https://CRAN.R-project.org/package=bundestag)

### About
`bundestag` adds curated data sets containing all available roll call votes of the German Bundestag, for the 16th, 17th, 18th and 19th electoral terms. 

### Installation
`bundestag` can be installed via GitHub:

```r
if (!require(devtools)) {
    install.packages('devtools')
}
devtools::install_github('erocoar/bundestag')
```

### Data
The data is named `bundestag` plus the respective electoral term. E.g.
```r
bundestag16 %>% 
  glimpse()
```

```r
Observations: 852
Variables: 107
$ `Fraktion/Gruppe` <chr> "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "BÜ90/GR", "...
$ Name              <chr> "Andreae", "Beck (Bremen)", "Beck (Köln)", "Behm", "Bender", "Berninger", "Bettin", "Bonde", "Cramon-Taubadel",...
$ Bezeichnung       <chr> "Kerstin Andreae", "Marieluise Beck (Bremen)", "Volker Beck (Köln)", "Cornelia Behm", "Birgitt Bender", "Matthi...
$ `16-80-1`         <chr> "nein", "ja", "ja", "ja", "ja", "ja", "ja", "ja", NA, "ja", NA, "ja", "ja", "ja", NA, "ja", "ja", "ja", "ja", N...
```
