![Sun Thoughts](https://github.com/YonatanRA/Sunspots-Solarflares-Project/blob/master/sol.jpg)

# Sunspots-Solarflares-Project

## Overview

The goal of this project is to find out the correlation between the sunspots and solarflares. My hipothesis is that correlation exists. 

---

## Data

The flares dataset is from [Kaggle](https://www.kaggle.com/heliodata/instruments-solarflares), thanks to [Arxiv](https://arxiv.org/abs/1703.04412). The dataset about sunspots is from the [Quandl](https://www.quandl.com/data/SIDC/SUNSPOTS_D-Total-Sunspot-Numbers-Daily) API.


## Workflow

For this project I build a pipeline with all functions to make the statatistics, plots and the report. Just executing the file main.py or main.ipynb all work is done.


## Results

The distribution of solar flares in time is shown in the next plot:

![Solar Flares](https://github.com/YonatanRA/Sunspots-Solarflares-Project/blob/master/barplot_flares.png)


The distribution of sunspots is:

![Sunspots](https://github.com/YonatanRA/Sunspots-Solarflares-Project/blob/master/barplot_spots.png)

The data for this project is from just one solar cycle, with its maximum in 2013, so is needed more info. It is not clear, but that plots look like a Normal Distribution in time.
The proportion of both flares and spots are as follow:

![dist flares](https://github.com/YonatanRA/Sunspots-Solarflares-Project/blob/master/distplot_flares.png)

![dist spots](https://github.com/YonatanRA/Sunspots-Solarflares-Project/blob/master/distplot_spots.png)


Both distributions look like a Poisson Distribution. That makes sense, after all both phenomena are "rare" events.
The next plot shows the flares classification. There is no data about A-class flares:

![Flare classes](https://github.com/YonatanRA/Sunspots-Solarflares-Project/blob/master/binning_class.png)


With this analysis, I've tried to find the correlation between solar flares and sunspots. For that I use Pearson, Spearman and Kendall correlations to look for linear and non-linear correlation. First, Pearson correlation:

![Pearson](https://github.com/YonatanRA/Sunspots-Solarflares-Project/blob/master/correlation%20Pearson.png)



