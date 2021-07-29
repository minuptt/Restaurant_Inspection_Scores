# Restaurant_Inspection_Scores

## Introduction

This project is copied from Data8.org, the original assignment can be found at github.com at: https://github.com/data-8/materials-su19/tree/master/materials/su19/hw/hw10.

In this project, we will explore a dataset that includes the dafety scores for restaurants in the city of Austin, Texas. We will be interested in determining the average score for the city from a random sample of the scores; the average restaurant score in out of 100. We'll compare 2 method for computing a confidence interval for that quantity: the bootstrap resampling method and an approximation based on the Central Limit Theorem.

The dataset includes 24367 replcations and 7 columns (Restaurant Name, Zip Code, Inspection Date, Score, Facility ID and Process Description). However, we just analyze based on 5 columns, so we will drop "Facility ID" and "Process Description" columns.

## Tasks

# 1.
Plot a histogram of the scores and compute the population mean from origin dataset.

# 2.
Imagine we instead had access only to a rnadom sample of 100 restaurant inspections. Therefore, we take the random 100 restaurants and create a new dataset, called rest_sample. We use this sample to estimate the population mean.
Plot a histogram of the scores and compute the sample mean from the sample dataset. 

# 3
Define function to take in an orginal table data, with a column Score and return the mean score of ONE resampleing from data.

# 4
Define a function to stimulate drawing 5000 resamples from rest_sample and compute the mean restaurant score in each resample and return an array of those 5000 resample means

# 5
Compute a 95% confidence interval for the average restaurant score using the array resampled_means

# 6
Plot Bootstrap sample mean histogram

# 7
Plot the relationship between resample means, interval and population mean

# 8
Calculate an interval around the sample mean that covers approximately 95% of the numbers in the resampled means array

