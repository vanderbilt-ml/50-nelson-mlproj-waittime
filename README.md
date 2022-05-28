# 50-nelson-mlproj-waittime

Alex Nelson
CS5262 - Summer 2022

## Goal:
As described in the Google Collab document in this repository, I would like to use previously collected and aggregated wait time data from Walt Disney World Resort to build a predictive model to help determine future wait times.

After looking through some of the available data (cited below) it appears that there is a data point captured every ~7.16 minutes. Giving us around ~55,000 entries per ride per year. There are 52 individual data sets (each representing a ride whose wait time was captured) with almost all data sets containing 5+ years of entries (300,000+ entries in each data set).

## Metrics:
Given the model that I intend on building for this project is a predictive model with scalar output and not a classification model, a confusion matrix is not applicable. Given the amount of data I have available for this project I would like to generate a generalized model for wait time predictions that is able to handle multiple individual rides (not necessarily all 52 as mentioned above, but hopefully more than one). However in the early stages I will likely be focused on creating a predictive model for an individual attraction. This means I will select an individual set of data and form my initial model from that data.

## Appendix:
[Source Data](https://touringplans.com/walt-disney-world/crowd-calendar)