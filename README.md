This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

This problem set is based on the paper “Price Points and Price Rigidity” from Daniel Levy, Dongwon Lee, Haipeng (Allan) Chen, Robert J. Kauffman and Mark Bergen (2011). It aims to teach you three elements of economic importance. First, it gives an introduction to the software and programming language R.   Second, it teaches essential data analysis skills. The third goal is to let you study an interesting economic everyday topic about prices.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
if (!require(devtools))
  install.packages("devtools")
source_gist("gist.github.com/skranz/fad6062e5462c9d0efe4")
install.rtutor(update.github=TRUE)

devtools::install_github("timo-sturm/RTutorPricePoints", upgrade_dependencies=FALSE)
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorPricePoints)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorPricePoints")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorPricePoints",
       load.sav=TRUE, sample.solution=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
