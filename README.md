# Predicted Finance&Securities Index Sector
### Abstract
This article has the purpose to educate factors affecting the stock price index of the finance and securities sector in the stock exchange of Thailand. A quantitative research model using secondary data, which is monthly quantitative data. There are 72 months from January 2017 to December 2022, and the research factors in this study are the exchange rate of the baht against the US dollar, Down Jones Index, United States 10-Year Bond Yield, United States 2-Year Bond Yield, Consumer Confidence Index, and Consumer price index using the multiple linear regression analysis to study the relationship between dependent and independent variables. 
It was found that factors affecting the stock price index of the finance and securities sector in the stock exchange of Thailand at the 0.05 level of statistical significance were the exchange rate of the baht against the US dollar, Down Jones Index, United States 10-Year Bond Yield, United States 2-Year Bond Yield, and Consumer price index. The knowledge discovered through this study can inform investors who want to invest in the finance and securities sector in the stock exchange of Thailand to know what factors affect the stock price index of the finance and securities sector and uses in investment planning. 

### Model score
#### Linear Regression 💎 **The best**
Train = 0.9137 
Test = 0.8215 

#### Ridge Regression 
Train = 0.9099 
Test = 0.8133 

#### Lasso Regression 
Train = 0.9136 
Test = 0.8204 

#### Gradient Boosting Regressor 
Train = 0.9996 
Test = 0.7818 

#### Random Forest Regressor 
Train = 0.9842 
Test = 0.8022 

#### Decision Tree Regressor 
Train = 1.0 
Test = 0.6593 

### Dataset Information
- **Dependent Variable**: the stock price index of the finance and securities sector
- **Independent Variables**:
  - Exchange rate (Baht/USD)
  - Inflation rate (CPI)
  - 10-year government bond yield
  - 2-year government bond yield
  - Consumer confidence index
  - General inflation rate

### Regression Model Summary

| Variable                              | Coefficient (β) | Std. Error  | t-Statistic | P-Value   |
|---------------------------------------|-----------------|-------------|-------------|-----------|
| Intercept                             | -8688.364       | 2689.696    | -3.230      | 0.002     |
| Exchange rate (Baht/USD)              | -161.004        | 35.943      | -4.479      | 0.000     |
| Down Jones Index                      | 0.125           | 0.016       | 7.974       | 0.000     |
| 10-year government bond yield         | 592.079         | 147.857     | 4.004       | 0.000     |
| 2-year government bond yield          | -578.824        | 128.337     | -4.510      | 0.000     |
| Consumer confidence index             | -0.357          | 10.225      | -0.035      | 0.972     |
| General inflation rate                | 142.357         | 38.115      | 3.735       | 0.000     |

#### Model Statistics:
- **R-squared**: 0.897
- **Adjusted R-squared**: 0.947
- **Standard Error of Estimate (SEE)**: 290.899
- **F-statistic**: 84.802
- **Significance (p-value)**: 0.000

