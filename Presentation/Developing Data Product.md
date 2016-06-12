Developing Data Product
========================================================
author: Owusu
date: 12-06-2016
autosize: true

ESTIMATING HOUSE PRICES
========================================================
PROBLEM

- Selling a house is ONE OF THE MOST STRESSFUL EVENTS in life.
- It was found to be even more stressful than bankruptcy, divorce or loss of someone you love.
- With the housing market finally recovering, many people are looking to sell their homes.
-     One way to avoid stress is to OFFER YOUR HOUSE AT A COMPETITIVE PRICE.

YET, HOW TO DETERMINE THE OPTIMAL PRICE FOR YOUR HOUSE?

Source: $Independent.co.uk$

SOLUTION: HOUSE PRICE ESTIMATOR
========================================================

- HOUSE PRICE ESTIMATOR (HPE) is an online platform which will help you estimate the value of your house on the market based on the following criteria: 
  + Construction Year,
  + Number of Bedrooms,
  + House Size,
  + Lot Size,
  + Location, and
  + Month when you plan to sell.

HOW DOES IT WORK?
========================================================


```r
library(nutshell)
data(sanfrancisco.home.sales)
str(sanfrancisco.home.sales)
```

```
'data.frame':	3281 obs. of  15 variables:
 $ line        : int  65083 4893 4959 27880 78680 17110 11363 56564 4964 30465 ...
 $ county      : Factor w/ 1 level "San Francisco County": 1 1 1 1 1 1 1 1 1 1 ...
 $ street      : Factor w/ 3227 levels "1 Burnett Avenue",..: 1 2 3 4 5 6 7 8 9 10 ...
 $ city        : Factor w/ 1 level "San Francisco": 1 1 1 1 1 1 1 1 1 1 ...
 $ zip         : int  94131 94134 94107 94109 94109 94107 94124 94103 94117 94110 ...
 $ date        : Date, format: "2008-06-11" "2009-06-12" ...
 $ price       : int  1470000 385000 1043000 560000 419000 552000 228000 2200000 1475000 565000 ...
 $ bedrooms    : int  3 0 2 2 NA NA 0 3 0 2 ...
 $ squarefeet  : int  2424 1304 1400 1149 NA NA 1060 2873 1225 660 ...
 $ lotsize     : int  NA 2143 NA NA NA NA 2247 3140 NA 2365 ...
 $ year        : int  1983 1945 1997 1988 1988 NA NA 1919 1918 1918 ...
 $ latitude    : num  37.8 37.7 37.8 37.8 37.8 ...
 $ longitude   : num  -122 -122 -122 -122 -122 ...
 $ month       : Factor w/ 18 levels "2008-02-01","2008-03-01",..: 5 17 17 12 2 14 16 7 17 11 ...
 $ neighborhood: Factor w/ 34 levels "Bayview","Bernal Heights",..: 31 32 30 34 34 30 1 16 13 2 ...
```

READY FOR YOUR FIRST ESTIMATION?
=======================================================

- Try the <House Price Estimator> now.

Thank you, and wish you an easy way to experience selling.
