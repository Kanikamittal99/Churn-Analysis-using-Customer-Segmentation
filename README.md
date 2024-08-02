# Churn Analysis Using Customer Segmentation in E-Commerce

## Problem Statement
In the e-commerce sector, customer churn represents a critical challenge that can significantly impact business sustainability and profitability. Understanding the factors leading to customer churn is essential for developing effective retention strategies. This project aims to analyze an e-commerce dataset to identify patterns and characteristics associated with customer churn, and to develop segmentation models that can help target at-risk customers and optimize marketing efforts.

**Dataset**: Ecommerce Customer Churn Analysis and Prediction [[source]](https://www.kaggle.com/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)

## Libraries Used
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations and data manipulation.
- **Matplotlib**: Plotting and visualization.
- **Seaborn**: Statistical data visualization.
- **Scikit-learn**: Machine learning algorithms and preprocessing.
- **SciPy**: Scientific and statistical functions.



## Goals 
**Reduce Customer Churn:** by identifing and targeting high-risk customers to improve retention and increase customer lifetime value, leading to enhanced revenue stability.

**Optimize Marketing Spend:** Use segmentation insights to allocate marketing resources more effectively, boosting ROI and driving higher engagement and conversions.

## Dataset Understanding 

| **Attribute** | **Data Type** | **Description** |
| --- | --- | --- |
| CustomerID | Integer | Customer ID |
| Churn | Integer | 1 means customer leave and 0 means customer uses the service |
| Tenure | Float | Tenure of customer in organization |
| PreferredLoginDevice | Object | Preferred login device of customer like laptop or phone |
| CityTier | Integer | City tier(1,2,3) |
| WarehouseToHome | Float | Distance in between warehouse to home of customer |
| PreferredPaymentMode | Object | Preferred payment method of customer |
| Gender | Object | Gender of customer |
| HourSpendOnApp | Float | Number of hours spend on mobile application or website |
| NumberOfDeviceRegistered | Integer | Total number of deceives is registered on particular customer |
| PreferedOrderCat | Object | Preferred order category of customer in last month |
| SatisfactionScore | Integer | Satisfactory score of customer on service |
| MaritalStatus | Object | Marital status of customer |
| NumberOfAddress | Integer | Total number of added added on particular customer |
| Complain | Integer | Any complaint has been raised in last month |
| OrderAmountHikeFromlastYear | Float | Percentage increases in order from last year |
| CouponUsed | Float | Total number of coupon has been used in last month |
| OrderCount | Float | Total number of orders has been places in last month |
| DaySinceLastOrder | Float | Day Since last order by customer |
| CashbackAmount | Float | Average cashback in last month |

<br>

## Project Outline
### 3.1 Data Collection and Preparation
- **Data Collection**: Obtain the e-commerce dataset containing customer attributes, transaction details, and churn status.
- **Data Cleaning**: Handle missing values, outliers, and inconsistencies using appropriate imputation methods.
- **Feature Selection**: Identify relevant features and remove redundant columns.

### 3.2 Exploratory Data Analysis (EDA) and Visualization
- **Descriptive Statistics**: Compute summary statistics for numerical and categorical features.
- **Correlation Analysis**: Use correlation tests to explore relationships between variables.
- **Visualizations**: Create plots to visualize data distributions and relationships (e.g., histograms, count plots).


## Insights
* This dataset has 5630 observations and 20 variables with 15 numerical variables, 5 categorical variables and 2 target variable.
* From the data visualization, it is obtained that the churn ratio has a correlation with tenure, complaints, cashback Amount, & preferred order cat.
* The results of predicting churn are strongly influenced by the level of Tenure, Complaint, Number of Addresses, and cashback Amount.


