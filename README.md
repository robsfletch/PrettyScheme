# Pretty Scheme Stata Package

*Still being edited heavily and far from a finished project. More schemes to come in the future hopefully. Definitely would be interested if other people want to contribute*

## Overview
This is a simple package that includes pretty schemes for graphing ins Stata


## Installation
To install this package, use the package https://github.com/haghish/github.

``` Stata
github install robsfletch/PrettyScheme
```

## Use
graphing commands in Stata can use different schemes through the *scheme()* option. For example, to use the main scheme in this package.

``` Stata
sysuse auto
scatter price mpg, scheme(pretty1)
```


## Uninstallation


``` Stata
github uninstall Pretty
```
