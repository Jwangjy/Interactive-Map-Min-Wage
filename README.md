# Interactive-Map-Min-Wage
Interactive Map of Minimum Wage in the US using Plotly in R

## Introduction
Apart from a single Linear Regressions group project, my Master's classes did not cover much data visualization and presentation. Hence, I wanted to do a series of small projects to practice different visualization methods and tools. This specific project was inspired by [DatasliceYT](https://www.youtube.com/watch?v=RrtqBYLf404) who created a similar visualization.

Data was taken from Department of Labor's [site](https://www.dol.gov/agencies/whd/state/minimum-wage/history) and [Kaggle](https://www.kaggle.com/lislejoem/us-minimum-wage-by-state-from-1968-to-2017). A secondary data set was downloaded to transform the State names to their State code via and inner join between the two data sets.

Libraries used:
library(plotly)
library(dplyr)
library(readr)
library(tidyverse)
library(htmlwidgets)

## Visualizations:
Three separate interactive visualizations were done:

nominal_minwage.html shows the change in nominal minimum wage for each US state from 1968 to 2020 in an interactive form. Minimum wage levels are visible for each year in the time frame.

relchange_minwage.html shows the percent change in real minimum wage for each state from 1968 to 2020.

relchangefed_minwage.html shows the percent change in real minimum wage relative to the percent change in real federal minimum wage for each state from 1968 to 2020.

## Code:
The code is tracked in the uploaded Rmd file titled Minwage.Graph.Rmd.

## Conclusions:
As seen in the visualizations, while nominal minimum wage has risen in most states, real minimum wage has actually decreased in many states. Even the Federal minimum wage has failed to keep pace with inflation through the years, seeing a decrease of 15.2% during this timeframe. More definitely needs to be done to ensure that minimum wage workers are able to maintain a decent standard of living.

Further analysis and thoughts can be found on my blog post 



