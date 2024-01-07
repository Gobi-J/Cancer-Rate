# Cancer Prediction: Mortality and Incidence Rates Classification

## Project Overview

Cancer, a complex and impactful health challenge, demands a comprehensive understanding of its prevalence and repercussions. Monitoring critical indicators like mortality and incidence rates is paramount for unraveling the dynamic nature of this disease over time. In this project, the synergy of machine learning algorithms with extensive datasets, encompassing patient demographics, medical histories, and genetic information, aims to provide a nuanced prediction of cancer incidence or mortality rates.

The primary objective revolves around predicting the status of cancer incidence or mortality rates, drawing insights from a diverse set of features. These include geographical factors, age-adjusted incidence rates, confidence intervals offering uncertainty estimates, the frequency of cancer cases, and recent trends signifying the direction of change.

## Dataset Attributes

- **ID:** A unique identifier for each entry, omitted during the modeling process.
- **Location:** Geographical information aiding regional analysis and capturing localized factors.
- **FIPS Code:** A standardized code for geographic identification, facilitating consideration of geographic variations.
- **Age-Adjusted Incidence Rate:** Cases per 100,000 people, adjusted for age, serving as a pivotal feature for prediction.
- **Confidence Intervals:** Lower and upper bounds providing insights into the uncertainty around incidence rates.
- **Average Annual Count:** The frequency of cancer cases, offering information about the prevalence of the disease.
- **Recent Trend:** Categories such as falling, stable, or rising, indicating the direction of change and serving as the target variable.
- **Recent 5-Year Trend:** An extended period for analyzing the directional change in incidence rates.
- **Confidence Intervals for 5-Year Trend:** Providing additional information about the uncertainty associated with the trend.

## Prediction Outcome

Cancer Status: Falling, Stable, Rising

## Technology Stack

- ***Language*** : Python 
- ***Middleware*** : Flask
- ***Data Collection*** : Kaggle
- ***Data Pre-processing*** - Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- ***Classification Algorithm*** : XGBoost with Hyper-parameter tuning
- ***Deployment*** : IBM Cloud
  
## Key Achievements

- The implemented model achieved an impressive predictive accuracy of 85%, utilizing the complete potential of the machine learning model.
- A thorough and comprehensive documentation process ensures the seamless transfer of knowledge and insights derived from the project, promoting transparency and understanding.
