## Household Expenditure Analysis

### Overview
This project analyzes the relationship between household expenditure and socio-economic factors using the LCF 2013 dataset.

### Dataset
- Living Costs and Food Survey (2013)  
- 5,144 households  
- Variables: expenditure, occupational class, tenure type, number of adults, number of children

The dataset used is the LCF 2013 teaching dataset provided for educational purposes.

### Methodology
- Data cleaning and preprocessing (pandas)  
- Exploratory data analysis (EDA)  
- Multiple Linear Regression (OLS) using statsmodels  
- Log transformation applied to improve model assumptions  
- Diagnostic tests (normality, heteroskedasticity, multicollinearity)  

### Key Results
- Household size (number of adults) is the strongest predictor of expenditure  
- Higher occupational class leads to higher spending  
- Owned and private rented households spend more than public rented  
- Log-linear model provides more reliable results  

### Tech Stack
- Python  
- pandas - data manipulation  
- numpy - numerical operations  
- matplotlib, seaborn - data visualization  
- statsmodels - regression modeling (OLS)  
- scipy - statistical tests    

### Notes
Group project completed as part of Mayerfeld Data Analysis Practicum.