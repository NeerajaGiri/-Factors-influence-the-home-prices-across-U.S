# US Housing Trends Analyzer and Influence Explorer

**Objective:**

Create a data science model to explain and predict U.S. home prices using key economic factors over the past 20 years.



**Steps**

1. **Data Collection:**

Used the S&P Case-Shiller Home Price Index from FRED as the home price proxy.

2. **Key Factors:**

Gathered publicly available data on factors influencing home prices nationally, including Per Capita GDP, Consumer Price Index (CPI), Construction Material Costs, Median Income, Subsidies, and Population Demographics, etc.

3. **Data Cleaning and Processing:**

Handled missing values, standardized dates, and addressed outliers.

4. **Exploratory Data Analysis (EDA):**

Conducted EDA to analyze variable distributions, correlations, and trends.

5. **Model Selection:**

Evaluated models including Linear Regression, ElasticNet, Random Forest, Gradient Boosting, SVR, and XGBoost.

6. **Model Training and Evaluation:**

Trained models on a subset of data and assessed them using MSE and R-squared metrics.

7. **Feature Importance:**

Analyzed feature importance in models such as Random Forest, XGBoost, and Gradient Boosting.

8. **Model Comparison:**

Compared models based on MSE and R-squared to determine the best performer.



9. **Visualization:**

Created visualizations to illustrate actual vs. predicted prices and feature importance.



10. **Conclusion:**

Identified the most effective model and key factors influencing home prices.



11. **Overall Implication:**

Enhanced understanding of factors affecting U.S. home prices over the past 20 years, aiding in robust predictive model development for the real estate sector.

# Results

The project involves understanding and predicting patterns rather than just describing historical trends or providing actionable recommendations.



# Data Availability

**The following variables are chosen for the study-**

1. Unemployment Rate
2. Employment Rate
3. Per Capita GDP
4. Real Median Household Income
5. Construction Prices
6. CPI
7. Interest Rates
8. Number of new houses supplied
9. Working Population
10. Urban Population
11. Percentage of population above 65
12. Housing subsidies
13. Number of Households

As a proxy to the home prices, S&P CASE-SHILLER Index is used.

Most of the data is downloaded from [https://fred.stlouisfed.org/].

**Following sources were used to gather data:**

CASE-SCHILLER Home Price Index - https://fred.stlouisfed.org/series/CSUSHPISA

Interest rates - https://fred.stlouisfed.org/series/FEDFUNDS

Unemployment rate - https://fred.stlouisfed.org/series/UNRATE

Working Population - https://fred.stlouisfed.org/series/LFWA64TTUSM647S

Employment rate - https://fred.stlouisfed.org/series/LREM64TTUSM156S

Consumer price index (CPI) - https://fred.stlouisfed.org/series/CPIAUCSL

Real Median Household Income - https://fred.stlouisfed.org/series/MEHOINUSA672N

Per Capita GDP - https://fred.stlouisfed.org/series/A939RX0Q048SBEA

Construction price index - https://fred.stlouisfed.org/series/WPUSI012011

percent urban population - https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS?end=2021&locations=US&start=2001

Housing Subsidies (Federal) - https://fred.stlouisfed.org/series/L312051A027NBEA

Total households - https://fred.stlouisfed.org/series/TTLHH


**Article referred** -

https://www.investopedia.com/articles/mortgages-real-estate/10/understanding-case-shiller-index.asp


**Research Paper referred** -

https://www.atlantis-press.com/article/25841966.pdf
