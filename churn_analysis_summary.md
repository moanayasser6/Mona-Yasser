#  Customer Churn Analysis (EDA Project)

##  Project Overview
This project performs Exploratory Data Analysis (EDA) on a telecom customer dataset to understand factors affecting customer churn behavior. The analysis focuses on data cleaning, statistical exploration, and visualization of both numerical and categorical features.

---
##  Dataset Overview
- Total Records: 7043  
- Final Cleaned Records: 7032  
- Features: 21 columns  
- Target Variable: Churn  
---
##  Data Cleaning
- No duplicate records found  
- Missing values found only in `TotalCharges` (11 values)  
- Converted `TotalCharges` to numeric  
- Removed or handled missing values  
---
##  Key Statistical Summary

###  Numerical Features:
- **Tenure:**
  - Mean: 32.42 months  
  - Range: 1 to 72 months  

- **Monthly Charges:**
  - Mean: 64.79  
  - Range: 18.25 to 118.75  

- **Total Charges:**
  - Mean: 2283.30  
  - Range: 18.80 to 8684.80  
---
##  Categorical Analysis Insights

### Customer Demographics:
- Gender: Almost balanced (Male: 3549, Female: 3483)  
- Senior Citizens: 16% of customers  
- Most customers do NOT have dependents  
---
### Services Distribution:
- Most customers use Phone Service (6352 users)  
- Fiber optic is the most used internet service  
- Many customers do not use Online Security or Tech Support  
---
### Contract Type:
- Month-to-month: 3875 (majority)  
- One year: 1472  
- Two year: 1685  

   Most churn risk comes from month-to-month contracts  
---
###  Payment Methods:
- Electronic check is the most common method  
- Other methods are evenly distributed  
---
### Target Variable (Churn):
- No: 5163 customers  
- Yes: 1869 customers  

 Dataset is imbalanced toward non-churn customers  
---
##  Key Insights
- Customers with **short tenure** are more likely to churn  
- **Month-to-month contracts** are strongly linked with churn  
- Lack of **online security & tech support** may increase churn risk  
- Fiber optic users show higher churn tendency  
- Dataset is slightly imbalanced (non-churn > churn)
---
##  Visual Analysis Included
- Histograms for numerical features  
- Boxplots for outliers  
- Countplots for categorical variables  
- Scatter plots for relationships  
- Correlation heatmap  
---
##  Tools Used
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
---
##  Project Goal
To identify key patterns and factors that influence customer churn and support business decision-making for customer retention strategies.
