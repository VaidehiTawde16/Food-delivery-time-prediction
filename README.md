# Food-delivery-time-prediction

This project aims to accurately predict food delivery times using various supervised machine learning regression techniques, with a focus on optimizing operational efficiency in the food delivery industry. The project achieved an impressive R² score of 0.81 using the XGBoost algorithm, showcasing the model's strong predictive performance.

## Project Overview
The primary goal of this project was to develop a machine learning model to forecast food delivery times with high accuracy. Leveraging a variety of supervised regression techniques, we aimed to build a robust predictive model that could handle the complexities of real-world delivery data. The model, trained on historical food delivery data, achieved a high R² score of 0.81 using the XGBoost algorithm.

## Tech Stack
Languages: Python

Libraries: scikit-learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn

Tools: Jupyter Notebook

## Data Preprocessing
Data preprocessing was a crucial step in this project. We performed extensive data cleaning, including handling missing values, outliers, and inconsistent entries. Feature engineering was applied to extract valuable insights from the raw data, such as encoding categorical variables and creating new features to capture important relationships in the data.

## Modeling Approach
We employed the following machine learning regression algorithms for model building:

Linear Regression

Lasso Regression

Ridge Regression

Decision Trees

Random Forest

Support Vector Regression

XGBoost

AdaBoost

Each algorithm was evaluated based on performance metrics like R² score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). After comparison, the XGBoost algorithm delivered the best performance, achieving an R² score of 0.81.

## Hyperparameter Tuning
To further enhance model performance, we used Grid Search Cross-Validation (CV) to optimize hyperparameters for Decision Trees and Support Vector Regression. This step significantly improved the accuracy and robustness of these models, demonstrating the importance of hyperparameter tuning in predictive modeling.

## Exploratory Data Analysis
Collaborating as a team, we conducted a comprehensive Exploratory Data Analysis (EDA) to uncover hidden patterns and insights in the dataset. EDA included:

Visualizing delivery time distributions

Analyzing correlations between features

Identifying key features impacting delivery times

These insights guided our feature engineering and model selection process, ensuring a solid foundation for building predictive models.

## Conclusion
Our project successfully developed a predictive model that accurately forecasts food delivery times, with XGBoost emerging as the top-performing algorithm. The high R² score of 0.81 reflects the model’s ability to predict delivery durations, potentially aiding businesses in streamlining their operations and improving customer satisfaction.

## Future Enhancements
Feature Selection: Further refining feature selection to identify the most impactful variables.

Model Optimization: Applying advanced techniques such as ensemble learning for even better performance.

Real-Time Deployment: Integrating the model into a real-time system for continuous learning and predictions based on live data.
