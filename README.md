# Black-Friday-Sales-Prediction
In this project, I have done EDA (graph visualization) on Black Friday sales dataset.  Performed data modelling, pre-processing, and applied a predictive algorithm which determines the purchase amount. XGBRegression had the best fit having the lowest error.

#### Dataset Information

This dataset comprises of sales transactions captured at a retail store. It’s a classic dataset to explore and expand your feature engineering skills and day to day understanding from multiple shopping experiences. This is a regression problem. The dataset has 550,069 rows and 12 columns.

**Problem:** To predict purchase amount

#### Attributes:
| Column ID |         Column Name        | Data type |           Description           | Masked |
|:---------:|:--------------------------:|:---------:|:-------------------------------:|--------|
|     0     |           User_ID          |   int64   |      Unique Id of customer      | False  |
|     1     |         Product_ID         |   object  |       Unique Id of product      | False  |
|     2     |           Gender           |   object  |         Sex of customer         | False  |
|     3     |             Age            |   object  |         Age of customer         | False  |
|     4     |         Occupation         |   int64   |   Occupation code of customer   | True   |
|     5     |        City_Category       |   object  |         City of customer        | True   |
|     6     | Stay_In_Current_City_Years |   object  | Number of years of stay in city | False  |
|     7     |       Marital_Status       |   int64   |    Marital status of customer   | False  |
|     8     |     Product_Category_1     |   int64   |       Category of product       | True   |
|     9     |     Product_Category_2     |  float64  |       Category of product       | True   |
|     10    |     Product_Category_3     |  float64  |       Category of product       | True   |
|     11    |          Purchase          |   int64   |         Purchase amount         | False  |

**Download link:** https://www.kaggle.com/kkartik93/black-friday-sales-prediction

#### Libraries used

<li>pandas
<li>matplotlib
<li>seaborn
<li>scikit-learn

#### ML Algorithms used

<li>Linear Regression
<li>Decision Tree
<li>Random Forest
<li>Extra Tress
<li>XGBRegression
  
