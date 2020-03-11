# Learning models from data: Mauna Loa CO2 record
[![Syzygy](https://img.shields.io/badge/launch-syzygy-important)](https://ubc.syzygy.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Flheagy%2Fubc-demo&urlpath=tree%2Fubc-demo%2Flinear-regression.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lheagy/ubc-demo/master?filepath=linear-regression.ipynb)

## Access

- UBC Students & Faculty: [![Syzygy](https://img.shields.io/badge/launch-syzygy-important)](https://ubc.syzygy.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Flheagy%2Fubc-demo&urlpath=tree%2Fubc-demo%2Flinear-regression.ipynb)
- or if you don't have a UBC CWL: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lheagy/ubc-demo/master?filepath=linear-regression.ipynb)

## Motivation: Climate Change

> _The climate emergency is one of the most pressing issues of our time. At this pivotal moment, the decisions and actions we take today will reverberate beyond our own borders and lifetimes._ -- [UBC Climate Emergency Engagement](https://climateemergency.ubc.ca/)

Carbon Dioxide (CO2) is a greenhouse gas, and significant contributor to the warming of the climate. It is an important input into climate models, which we use to make predictions about possible future climate scenarios, and sometimes to make policy decisions, including carbon taxes. 

**Question:** Based on historical CO2 data, can we predict what CO2 concentrations will be in the future? 

## Learning Goals
- explore the idea of "learning": building a model from data that lets us make predictions 
- introduce the principles of linear regression, a simple, but powerful method for estimating a linear model of data
- explore the impact of outliers in data on the model 
- discuss the limitations of models

## Context

Scripps institute of Oceanography has a research station at Mauna Loa in Hawaii where they have been measuring atmospheric CO2 since 1958. The data we will focus on are the seasonally adjusted data. 

<img src="https://scrippsco2.ucsd.edu/assets/images/mlo_station_map.png" align="center">

**Data Source**

C. D. Keeling, S. C. Piper, R. B. Bacastow, M. Wahlen, T. P. Whorf, M. Heimann, and  H. A. Meijer, Exchanges of atmospheric CO2 and 13CO2 with the terrestrial biosphere and  oceans from 1978 to 2000.  I. Global aspects, SIO Reference Series, No. 01-06, Scripps  Institution of Oceanography, San Diego, 88 pages, 2001. https://scrippsco2.ucsd.edu/data/atmospheric_co2/primary_mlo_co2_record.html   

## Running the notebook
- Each block of code can be run with `shift` + `enter` or from the menu with `Cell` + `Run Cells`
- If you need to restart the notebook, go to the menu: `Kernel` + `Restart`. 
