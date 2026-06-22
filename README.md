
# House Price Prediction Using Machine Learning

## Project Overview

This project focuses on predicting house prices using machine learning techniques. The dataset contains information about different properties, including area, number of bedrooms, bathrooms, parking spaces, furnishing status, and other amenities. The goal of the project was to understand the factors that influence house prices and build a model capable of making accurate predictions.

## Dataset Description

The dataset includes various features that describe residential properties. Some of the important attributes are area, bedrooms, bathrooms, stories, parking availability, furnishing status, air conditioning, preferred area, basement availability, and other facilities. The target variable is the house price.

## Data Preprocessing

Before building the models, the dataset was explored and cleaned. Missing values and data types were checked to ensure the data was suitable for analysis. Categorical features such as furnishing status and facility-related columns were converted into numerical values so that machine learning algorithms could process them effectively.

After preprocessing, the target variable (price) was separated from the remaining features, and the dataset was split into training and testing sets.

## Exploratory Data Analysis

Several visualizations were created to better understand the dataset and identify patterns.

### Price Distribution

The price distribution showed that most houses fall within a moderate price range, while a smaller number of properties have significantly higher prices. This indicates a positively skewed distribution.

### Correlation Analysis

A correlation heatmap was used to examine the relationships between different features and house prices. The analysis revealed that area has a strong positive relationship with price. Bathrooms, bedrooms, and certain amenities also showed a noticeable impact on house value.

### Actual vs Predicted Prices

A scatter plot comparing actual and predicted prices was used to evaluate model performance. Most predictions followed the overall trend of the actual prices, indicating that the model was able to capture the relationship between property features and market value.

## Model Development

Two machine learning algorithms were used in this project:

### Linear Regression

Linear Regression was used as a baseline model to understand the linear relationship between house features and prices. It provided a simple and interpretable approach to prediction.

### Random Forest Regressor

Random Forest Regressor was implemented to capture more complex relationships within the data. Since it combines multiple decision trees, it is capable of handling non-linear patterns and interactions between features.

## Model Evaluation

The models were evaluated using common regression metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.

After comparing the results, Random Forest Regressor performed better than Linear Regression. Its predictions were generally closer to the actual house prices, making it the more effective model for this dataset.

## Key Findings

The analysis showed that the area of a property is one of the most important factors affecting house prices. Houses with larger areas generally have higher market values.

The number of bathrooms and bedrooms also contributes significantly to the final price. In addition, amenities such as air conditioning, furnishing status, parking facilities, and preferred locations influence property value.

An interesting observation was that some houses with similar areas had noticeably different prices. This suggests that factors such as amenities and location also play a major role in determining house prices.

## Conclusion

This project provided practical experience in data preprocessing, exploratory data analysis, machine learning model development, and model evaluation. It demonstrated how machine learning can be applied to solve real-world problems in the real estate domain.

Among the models tested, Random Forest Regressor achieved the best performance and produced more accurate predictions. Overall, this project helped strengthen my understanding of the complete machine learning workflow, from data preparation to model evaluation and interpretation.
