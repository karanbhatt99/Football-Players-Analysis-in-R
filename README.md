# Football-Players-Analysis-in-R
This project aims to analyze the overall performance of football players using FIFA football player dataset. The primary objective is to predict the overall performance score of players based on various skills. The analysis employs two machine learning algorithms: Linear Regression and Random Forest Regression. The project is implemented using the R programming language in the R Studio IDE, chosen for its superior capabilities in statistical computing and graphics.

## Dataset Selection:
The FIFA football player dataset is selected for this analysis, containing information about different player attributes, such as skill levels, positions, and playing styles.

## Required Packages:
Several R packages are utilized in this project for data manipulation, visualization, and modeling:

- ggplot2: A package for creating graphical plots.
- gridExtra: Provides additional functionality for graph plotting.
- moments: Used for statistical moments calculation.
- devtools: Assists in package development.
- corrplot: Facilitates the creation of correlation matrix graphs.
- dplyr: A package for data manipulation.
- randomForest: Utilized to build a random forest regression model.
- metrics: Offers various metrics for regression tasks.

## Modeling and Analysis:
Two machine learning algorithms are employed for predicting overall performance:

### 1. Random Forest Regression:
Random Forest Regression is an ensemble learning algorithm that constructs a multitude of decision trees during training and outputs the average prediction of the individual trees for regression tasks. It excels in handling complex relationships within data and mitigates overfitting by aggregating predictions from diverse trees. Random Forest Regression is particularly effective in capturing non-linear patterns and delivering robust performance in predictive modeling.

### 2. Multiple Linear Regression:
   Multiple Linear Regression is a statistical technique used for modeling the relationship between a dependent variable and two or more independent variables. It assumes a linear relationship and aims to find the best-fitting linear equation to predict the target variable based on the input features. This method provides insights into the individual and collective impact of various predictors on the response variable.

## Cross-Validation:
To ensure model accuracy, a cross-validation method is used, where the model is evaluated on unseen testing data. Metrics such as RMSE, MAE, and R-Square are employed to assess the performance of both models.

## Conclusion:
This report presents a statistical analysis of FIFA football player data, focusing on predicting overall performance using machine learning algorithms. The dataset undergoes preprocessing, including integration, cleaning, transformation, and reduction. Two models, random forest regression and multiple linear regression, are applied to the data, with random forest showing slightly higher accuracy. Evaluation metrics and visualizations in the "analysis.nb.html" file provide a comprehensive understanding of the results.
