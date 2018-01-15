# Pretty Scheme Stata Package

*Still being edited heavily and far from a finished project. More schemes to come in the future hopefully. Definitely would be interested if other people want to contribute*

## Overview
This is a simple package that includes pretty schemes for graphing ins Stata. Information about schemes can be found at https://www.stata.com/manuals13/g-4schemesintro.pdf, but essentially it means changing the aesthetics of Stata graphs.


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

# Related project
This scheme is heavily used in my more extensive graphing project, **Pretty**, available at https://github.com/robsfletch/pretty. That package uses the pretty1 scheme as its default if you are interested in having that scheme as a default scheme when you graph in stata.

## Uninstallation


``` Stata
github uninstall Pretty
```
