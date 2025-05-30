## This repository contains all code, data preparation steps, and analysis related to my master’s thesis on the effect of tram network expansion on housing prices in Greater Manchester between 1995 and 2024.

### The aim of the thesis is to evaluate whether proximity to newly opened tram stops causes nearby housing prices to increase or decrease. The core research design is a staggered Difference-in-Differences event study with two-way fixed effects, comparing log housing sale prices for properties located within 0–1000 meters (treatment group) to those 1000–1500 meters away (control group), before and after the nearest tram stop opened.

### The housing data was obtained from the HM Land Registry and includes over 100,000 transactions from 1995 to 2024. After geocoding and cleaning, the analysis focuses on a final panel of approximately 25,000 transactions located near tram stops. Tram stop coordinates were sourced from Transport for Greater Manchester and manually matched with opening years based on official reports and documents.

### All data manipulation, treatment assignment, and regression estimation were performed in R. The analysis includes fixed effects for both year and spatial rings, clustered standard errors, and graphical output from an event study regression.

### The results indicate that, on average, the opening of tram stops does not have a strong or sustained effect on local housing prices. One year after treatment, there is a statistically significant but modest dip in prices, possibly reflecting short-run market adjustments. The longer-run effects are close to zero and not statistically significant.

### This repository is intended as a public demonstration of applied data analytics in urban economics.

### All data wrangling, merging, and filtering steps are explained in detail in the full thesis (to be uploaded upon completion)
