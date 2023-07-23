This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

In this problem set, we will explore an intriguing question: Does air pollution affect criminal activity? It is based on the paper "Air Pollution and Criminal Activity: Microgeographic Evidence from Chicago" which was published in the Journal of American Economic Journal: Applied Economics (2021).  Their main finding is that air pollution increases violent crime by 1.9 % on the downwind side of highways compared to the upwind side.Besides, you will improve your knowledge about R and economic methods.

The paper can be found under the link https://www.aeaweb.org/articles?id=10.1257/app.20190091

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("JanaRuss/RTutorAirPollutionCriminalActivity")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorAirPollCrime)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorAirPollCrime")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorAirPollCrime",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
