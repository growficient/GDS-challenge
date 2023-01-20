# GDS-challenge

Inside this file you will start working your way through the Growficient
Data Scientist challenge, or GDS in short. This challenge is meant to serve
as a precursor-look towards your data scientist skills

## Introduction

It is the beginning of 2013, and you're a new stock trader looking to make some
quick bucks. You've found something that piqued your interest, namely "coin X". 
You managed to scrape together some historical exhange-rates of coin X and 
another coin, and now you're almost
ready to hedge your bets. But there's a problem, the finance tool 
you've been using has stopped working! Without this you can't tell how 
the price is evolving, and you have no graphs to inspect anymore.
While you wait for it to be fixed, you are left with only one solution, to
predict the future, because how else are you going to get rich?

## Tasks

Your task is to implement a forecasting model to predict the future prices of
asset X up until the end of 2017.

### How to start

1. Fork this repository
2. Install the dependencies (python 3.10+ currently) using the Poetry package manager
3. Continue below

### Checklist

1. Clean and inspect your datasets, and describe your steps.
2. Choose or build a forecasting model, and explain how it works
3. Predict the daily price of asset X until the end of 12-31-2017, starting
from 01-01-2013
4. Plot your predictions together with the original data
5. Evaluate your model using `test.csv`, explain the metric you chose and why

### Restrictions

1. Use Pandas for dataset handling, apart from these use any package you want.
2. You will not use any other training data than `train.csv`
