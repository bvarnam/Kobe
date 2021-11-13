# Kobe Bryant Shot Predictions Hackathon (with updates)
---

## Project Background
This project aims to predict whether or not Kobe Bryant will make or miss a shot given data denoted by the data dictionary provided below. This project was intentially done in a short amount of time, solo, without outside supervision or guidance (outside of stackoverflow and documentation).

In summary, this project aims to show what can be accomplished in the data science process in a short period of time with a particular focus on exploratory analysis, feature engineering, and a variety of classification modeling types.

This project was obtained through Kaggle:
- [Kobe Bryant Shot Selection](https://www.kaggle.com/c/kobe-bryant-shot-selection)


## Contents
```code``` contains the python jupyter notebooks used to conduct the process and are labeled both in the order they were completed and what they are performing. Skip to the last notebook, '07_Analysis-and-Conclusion' for a summary of the modeling processes and final conclusions.


## Software Packages
- ```pandas``` for data handling and cleaning.
- ```numpy``` for mathematical manipulations and calcuations.
- ```scikitlearn``` for model preprocessing, selection, and training.
- ```tensorflow``` for neural network creation and modeling.
- ```XGBoost``` for extreme gradient boost modeling.
- ```matplotlib``` for visualizations of analysis.
- ```seaborn``` for additional visualizations of analysis.


## Datasets
The dataset was provided through the kaggle page linked in **Project Background**. As stated on said page under Data Description, "This data contains the location and circumstances of every field goal attempted by Kobe Bryant took during his 20-year career."


## Data Dictionary
**Final Dataset**
|Feature  | Datatype |Description |
--- | --- | --- 
|combined_shot_type | str object | What type of shot was taken. (ex. Jump shot, Dunk) |
|period | int | Which period the shot was taken in. |
|shot_distance | int | How far from the basket the shot was taken from. |
|shot_made_flag | int | Whether or not the shot was made (Target). |
|shot_type | str object | 2point or 3point shot |
|shot_zone_area | str object | Which part of the floor the shot was taken from. (ex. Left Side, Right Side, Center,...) |
|shot_zone_basic | str object | General zone the shot was taken in related to distance from basket. (ex. Mid-Range, Restricted Area,...) |
|shot_zone_range | str object | How far the shot was taken from the basket categorized by range. (ex. Less Than 8 ft., 8-16 ft.,...) |
|opponent | str object | Season and city of opposing team. |
|home_away | str object | Whether Kobe was playing at Home Stadium or away. |
|time_sec_remaining | int | How many seconds remain in the period. |