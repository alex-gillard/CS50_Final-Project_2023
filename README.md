# Comparative Analysis of Machine Learning Regression Models on Wine Quality - README.md

### By Alex Gillard
#### Kelowna, British Columbia, Canada

#### Video Demo: https://www.youtube.com/watch?v=QRU00DBsarI
#### Description:

Note: It is recommended to read the entire README.md file prior to watching the video demo

## Project Overview

The project "Comparative Analysis of Machine Learning Models on Wine Quality" is a comprehensive report focusing on the field of machine learning (ML) with applications to wine quality assessment. This project serves as a final submission to the Harvard/edX CS50 course and aims to introduce beginner wine tasters to ML, enabling them to make informed decisions when selecting wines. This report leverages popular data science libraries from Python such as Pandas, Seaborn, and Scikit-Learn, to analyze a well-known dataset from Kaggle, focusing on physicochemical tests of wine attributes and their corresponding quality scores.

## Problem Statement

This project addresses the challenges faced by new wine tasters in understanding and interpreting the range of factors which influence wine quality. By learning the process of setting up ML models and examining the results of relevant wine literature, this project seeks to not only outline the most relevant attributes of wine towards quality, but to evaluate the most suitable ML model for predicting influential wine attributes towards wine quality. Moreover, this approach aims to simplify the process of wine selection for novices.

## Methodology

This project takes on a structured approach, beginning with data exploration and pre-processing, followed by feature selection, model training, evaluation, and comparison. Two ML regression models are employed:

1. Decision Tree Regression
2. Random Forest Regression

The models are assessed on Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) scores to identify the most effective model towards predicting wine quality.

## Hypothesis

This report hypothesizes that the Random Forest Regression will outperform the Decision Tree Regression model, indicated by lower RMSE and MAE scores.

## Project Structure

The project is structured into several key components, each significantly contributing towards the analysis:

1. **Data Exploration and Pre-Processing:** The Wine Quality Dataset will be examined where the data will be cleaned along with handling outliers and skewness. The dataset is split into two separate dataframes: One dataframe contains log-transformed (LT) wine attributes while the second dataframe contains domain-informed (ST) wine attributes chosen after feature selection.

2. **Feature Selection:** Based on consumer studies and wine literature, relevant attributes influencing wine quality are selected for analysis.

3. **Model Training:** The selected features are used to train both the Decision Tree and Random Forest models

4. **Model Evaluation and Comparison:** The models are evaluated using the MAE and RMSE metrics and their performance is compared. Additionally, each model is compared when using both LT and ST dataframes during the process of training and evaluation to examine the effects of data transformation on model performance.

## Files of Importance

- **WineQT.csv:** The primary dataset used for analysis

- **CS50_Final-Project_AG.ipynb:** The Jupyter Notebook containing the code used for data pre-processing, visualization, model training, and evaluation. Additionally contains a dedicated discussion section outlining the rationale behind this project.

- **README.md:** The current doccument which provides a detailed overview of this project

## Design Choices & Justifications

Several critical design choices were made during the project:

- **Selection of Regression Models:** Decision Tree and Random Forest models were chosen due to their suitability for handling continuous variables and their robustness in dealing with non-parametric data.

- **Feature Selection Based on Wine Literature:** Features were chosen based on insights from consumer preference studies of *Vinho Verde* wine varieties from Portugal which is where the Wine Quality Dataset originates its data from. This ensures the feature selection is rooted in real-world wine tasting experiences.

- **Data Pre-Processing Techniques:** Log-transformation and handling of skewness were applied to improve model accuracy.

## Conclusion

This project demonstrates the use of ML in predicting wine quality. These findings indicate that the Random Forest model, trained with carefully selected features effectively achieves low error scores, validating the initial hypothesis.

## Future Work

Future iterations of the project could explore additional parametric statistical tests, different data pre-processing techniques, and alternative ML models employing a classification approach to the Wine Quality Dataset using methods such as K-Nearest Neighbours (KNN).

## Acknowledgements

I would like to sincerely thank Dr. David Malan and the CS50 preceptors for providing the excellently taught lessons, conceptual explanations, and resources by the CS50 course which developed the foundation to successfully execute this project. I will continue to use the skills I have been fortunate enough to learn from this course for the professional development towards my M.Sc. studies and beyond!
