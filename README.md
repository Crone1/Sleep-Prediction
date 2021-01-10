# Project Explanation
The project was done by myself and GitHub users *'adampower48'* and *'liamcarroll'* as part of the module *'Advanced Machine Learning'*. The purpose of this project was to model and predict a subjects sleep stage at a point into the future based on their Apple Watch data and their previous sleep states. The data recorded by this Apple Watch was the subjects heart rate, their step count and their acceleration in all directions and we also have a manually assigned sleep stage label for each datapoint. These sleep labels ranged from 0-5 with 0 being awake and 5 being REM sleep.

Before starting the project we performed a lit review on previous sleep stage prediction that had already been done.
The code for completing this time-series prediction task was then done using google collab for collaboration purposes and to get experiance using this platform. Afterwards, I coppied the developed code into this GitHub repository.

# Notebook Explanation
This code consists of two notebooks:

1. The Data Preperation (data_prep.ipynb)
   - The data was not in the nicest of formats so this involved a lot of code to format it properly.
2. The Sleep Prediction (forecasting.ipynb)
   - We used many different models for this and go through the different results here. We also perform several experiments with configuration.
