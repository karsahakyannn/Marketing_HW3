Analysis Overview
This report details the examination of a dataset from a telecommunications firm, with a specific focus on customer retention and calculating Customer Lifetime Value (CLV) based on various determinants.

Data Setup
The data was initially processed to ensure quality:

Removal of unnecessary columns such as 'ID'.
Transformation of categorical data via one-hot encoding.
Survival Analysis
We applied several statistical models to analyze customer retention:

Models used: Weibull, Lognormal, Exponential, and LogLogistic.
Model selection was based on the Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC), with the Lognormal model proving most effective.
Customer Lifetime Value (CLV) Estimation
CLV was estimated using the selected Lognormal model, considering:

A monthly margin assumption of $1000 and a discount rate of 20%.
Focus was maintained on key columns relevant to CLV estimation.
Analysis Insights
Influence of Marital Status:

Married customers showed a higher CLV, suggesting a reduced risk of churn.
Noticeable differences were observed in CLV distribution between married and unmarried customers.
Gender Dynamics:

Gender had a minor impact on CLV.
A more distinct peak in CLV was noted among female customers.
Educational Influence:

Education levels presented varied CLV distributions.
Customers with lower education levels exhibited higher CLVs.
Customer Category Insights:

Significant differences in CLV across customer categories were noted.
Customers in the 'Plus service' category had the highest CLV.
Effect of Internet Service:

Customers lacking internet service displayed increased CLVs.
Conclusion
This comprehensive analysis underscores key demographics and service preferences that influence customer retention and lifetime value in a telecom context. It emphasizes the need to factor in various customer attributes and service options when assessing customer value and behavior.
