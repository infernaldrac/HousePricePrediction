# House Price Prediction

## Project Overview

This project predicts house prices using Machine Learning techniques. The objective was to analyze housing data, identify important factors affecting property prices, and compare the performance of different regression models.

## Dataset

* Housing Prices Dataset (Kaggle)
* 545 records
* 13 features

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Models Used

1. Linear Regression
2. Random Forest Regressor

## Results

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | 0.6529   |
| Random Forest     | 0.6133   |

Linear Regression performed better and was selected as the final model.

## Summary 
The analysis revealed that features such as area, number of bathrooms, parking availability, air conditioning, and location-related factors had the strongest influence on house prices. Among the models tested, Linear Regression performed better than Random Forest, achieving an R² score of approximately 0.65, which means the model was able to explain about 65% of the variation in house prices. The prediction errors were reasonable considering the limited number of features available in the dataset. One surprising observation was that amenities such as air conditioning and preferred area had a noticeable impact on property prices in addition to house size. Based on these findings, real estate businesses should focus on highlighting property size, location advantages, and key amenities when pricing and marketing homes, as these factors significantly affect market value.

## Visualizations

* House Price Distribution
* Correlation Heatmap
* Actual vs Predicted House Prices

## Author

Aarsh Pavashiya
# HousePricePrediction
