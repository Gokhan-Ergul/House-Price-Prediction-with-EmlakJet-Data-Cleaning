# House-Price-Prediction-with-EmlakJet-Data-Cleaning
##  You can visit my kaggle [page](https://www.kaggle.com/code/gokhanergul/house-price-prediction-with-emlakjet-data-cleaning)  to see my presentation

## Project Overview
This project aims to predict house prices using real estate data sourced from EmlakJet. The data goes through extensive preprocessing and feature engineering steps, including data cleaning, normalization, and transformation using techniques like Box-Cox. The goal is to build a robust machine learning model with high predictive performance.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#Features)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Normalization and Transformation](#normalization-and-transformation)
- [Modeling](#modeling)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [Conclusion](#conclusion)
- [Contact](#contact)

## Dataset
The dataset was sourced from [EmlakJet](https://www.emlakjet.com/) and contains information about various properties including location, size, price, and additional features. 

### Features:
- **Location**: City, neighborhood, and region information.
- **Size**: Property size in square meters.
- **Price**: The price of the property in Turkish Lira.
- **Other Features**: Number of rooms, number of bathrooms, building age, etc.

## Data Cleaning
In this step, we addressed various data quality issues such as:
- **Handling Missing Values**: Missing data was either imputed using the median/mean method or removed if deemed irrelevant.
- **Outlier Detection and Removal**: We identified outliers using Z-scores and IQR methods and removed them to improve model performance.
- **Data Type Corrections**: Certain features were cast to appropriate data types (e.g., categorical variables were encoded with **Target encoding**).

## Feature Engineering
Feature engineering is one of the key steps in this project. The following techniques were applied:
- **Feature Creation**: New features were generated based on existing ones, such as price per square meter.
- **Target Encoding**: Categorical variables like location and property type were Target encoded to be used in machine learning models.
- **Log Transformation**: Features with a high degree of skewness were transformed using logarithmic scales.

## Normalization and Transformation
To ensure that the model converges faster and performs optimally, various normalization and transformation techniques were applied:
- **Standard Scaling**: Continuous features were scaled using StandardScaler.
- **Box-Cox Transformation**: Certain skewed features were transformed using the Box-Cox method to normalize their distribution.




## How to Run
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/house-price-prediction-emlakjet.git
   ```
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Run the notebook or Python script:
   ```
   jupyter notebook Data_Cleaning.ipynb
   ```

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn for visualization

## Conclusion
This project demonstrated the importance of data cleaning and feature engineering in building a successful predictive model. The application of Box-Cox transformation and normalization techniques helped in improving the model's performance.

## Contact
If you have any questions or suggestions, feel free to reach out to me:
- **Email**: gokhannergull@gmail.com

