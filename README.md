# Heart Disease Prediction – Exploratory Data Analysis
This project analyzes the Statlog (Heart) Dataset from the UCI Machine Learning Repository to explore the factors associated with heart disease. The goal of this analysis is to perform exploratory data analysis (EDA), clean the dataset, perform feature engineering, and develop a baseline machine learning model for heart disease prediction.

## How to get started
In order to get this project running please download the code using the git clone command

  - 'git clone git@github.com:ashrivastav33/heart-disease-eda-ml.git'

## Note
- We are making an assumption you already are familiar with using Jupyter Notebook using tools like Google Colab or Jupyter etc.
- You will need an internet connection to download/read the dataset or csv file

## Project Structure

### - /data/data.csv                                   ---> Stores the dataset used for this project
### - /code/heart-disease-eda-ml.ipynb                 ---> Stores the code/jupyter notebook used for this project

# Dataset

  - Source: Statlog (Heart) Dataset from the UCI Machine Learning Repository
  - The dataset contains 270 observations with 13 medical attributes and 1 target variable indicating the presence or absence of heart disease.

# Objectives
 - Perform data cleaning and preprocessing
 - Conduct exploratory data analysis (EDA)
 - Identify relationships between medical attributes and heart disease
 - Perform feature engineering
 - Develop a baseline machine learning classification model

## Results

The baseline model achieved the following results:
 - Accuracy: 0.8704
 - ROC-AUC: 0.9466

These results indicate that the model performs well at distinguishing between patients with and without heart disease. 
The high ROC-AUC score suggests strong classification capability across different probability thresholds.

## Conclusion

- Chest pain type appears strongly correlated with heart disease diagnosis.
- Age and maximum heart rate show meaningful distribution differences between patients with and without heart disease.
- Several variables show moderate correlations with the target variable.
- Logistic Regression serves as a strong baseline classification model.

### Learning

- This was a fun and helpful learning exercise that made it easier to understand how how to predict heart disease as they seem to be a common factor these days due to lifestyle
  
## Next Steps and Recommendations

 - We can explore more scenarios to learn meaningful insights
 - Further improvements could include:
     - Testing additional models such as Random Forest, Gradient Boosting, or Support Vector Machines.
     - Performing hyperparameter tuning to improve predictive performance.
     - Applying feature scaling and advanced feature engineering techniques.
