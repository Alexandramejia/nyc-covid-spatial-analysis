# NYC COVID Spatial Analysis

This project explores how COVID-19 cases vary across New York City using spatial data.

## Overview

In this project, I combined several datasets, including ZIP code boundaries, COVID-19 case data, food retail locations, nursing homes, and census (ACS) data. The goal was to see how COVID-19 case counts relate to population patterns and neighborhood characteristics.

## What I built

* Static maps comparing COVID-19 cases with other variables
* An interactive map using Leaflet with multiple layers:

  * COVID-19 cases
  * Elderly population
  * Nursing homes

## Live Project (RPubs)

👉 http://rpubs.com/alexandramejia/1416647

## Tools Used

* R
* tidyverse
* sf
* ggplot2
* leaflet

## Key Takeaway

From the maps, COVID-19 cases are higher in more densely populated areas, especially in parts of Brooklyn and the Bronx. These areas also tend to have more activity and local resources, which may lead to more interaction between people. While this doesn’t prove cause and effect, it shows that population and neighborhood patterns are connected to how cases are distributed.

## Files

* `Week_09.qmd` – main analysis
* `Week_09.html` – full report
