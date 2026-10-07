<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
  <img src="assets/banner-light.png" alt="Michael Mancini: Data Science, Machine Learning, SQL" width="100%">
</picture>

<br>

I'm an Applied Mathematics student at York University focused on data science. I like projects that start with messy, real-world data and end with something people can use: a model with honest error bars, a live app, or a dashboard.

- **What I do:** data cleaning, feature engineering, machine learning, SQL analysis, and turning results into apps and dashboards
- **How I work:** start from a simple baseline, compare models fairly, and explain where a model is unreliable, not just where it's accurate
- **Next up:** per-car explanations (SHAP) and a Streamlit app for my used car deal detector
- **Looking for:** data science and analytics roles

<!--
  Contact badges: replace the links below and delete these comment lines to show them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logoColor=white)](https://www.linkedin.com/in/YOUR-PROFILE)
[![Email](https://img.shields.io/badge/Email-24292f?style=flat-square&logo=gmail&logoColor=white)](mailto:YOUR-EMAIL)
-->

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/MichaelMancini9/used-car-deal-detector"><img src="assets/used-car-deal-detector.png" alt="Chart of Strong deals: listed prices below each car's fair price range"></a>

### [Used Car Deal Detector](https://github.com/MichaelMancini9/used-car-deal-detector)

Estimates a fair price **range** for 750k used car listings and flags cars priced below it, while separating real bargains from listings that are cheap for a reason (accidents, data errors, classics).

**7.7% pricing error** vs 12.1% for a comparable-sales baseline · ranges calibrated to **80% coverage**

<sub>Python · pandas · LightGBM · quantile regression · conformal calibration</sub>

</td>
<td width="50%" valign="top">

<a href="https://github.com/MichaelMancini9/Bike-Sharing"><img src="assets/bike-sharing.png" alt="Power BI dashboard of bike rental demand and model performance"></a>

### [Bike Sharing Demand](https://github.com/MichaelMancini9/Bike-Sharing)

Predicts hourly bike rental demand from weather and time of day. Compared five models with cross-validation, then shipped the best one as an app, an API and a dashboard.

**R² 0.93** (Random Forest) · [**Live demo**](https://bike-sharing-wyhns57zrmhi7vahzdzyvq.streamlit.app/) · FastAPI endpoint · Power BI dashboard

<sub>Python · scikit-learn · XGBoost · Streamlit · FastAPI · Power BI</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/CMSOTO2/global-development-dashboard"><img src="assets/global-development-dashboard.png" alt="World map of GDP growth by country from the Global Development Dashboard"></a>

### [Global Development Dashboard](https://github.com/CMSOTO2/global-development-dashboard)

Full-stack dashboard for exploring GDP growth, inflation, life expectancy and poverty across 217 countries. Team project with [@CMSOTO2](https://github.com/CMSOTO2): **I built the data pipeline**, cleaning and reshaping World Bank data and loading it into the SQLite database behind the API.

[**Live app**](https://global-development-dashboard-production.up.railway.app/)

<sub>Python · pandas · SQLite · React / TypeScript (frontend by teammate)</sub>

</td>
<td width="50%" valign="top">

<a href="https://github.com/MichaelMancini9/NYC-TAXI-SQL"><img src="assets/nyc-taxi-sql.png" alt="Bar chart of NYC taxi trips by pickup hour"></a>

### [NYC Taxi Analysis](https://github.com/MichaelMancini9/NYC-TAXI-SQL)

SQL analysis of NYC taxi trips: when demand peaks, how boroughs differ, and what really drives fares.

Demand peaks at **5–6 PM** · fares follow **distance far more than time** · Manhattan has the highest fare per mile

<sub>SQL (SQLite) · Python · pandas · seaborn</sub>

</td>
</tr>
</table>

**Also:** [Telecom Customer Churn Prediction](https://github.com/MichaelMancini9/Telecom-Customer-Churn-Prediction): Random Forest classifier (ROC-AUC 0.84) showing contract type, tenure and monthly charges drive churn.

## Tools

![Python](https://img.shields.io/badge/Python-24292f?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-24292f?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-24292f?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-24292f?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-24292f?style=flat-square&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-24292f?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-24292f?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-24292f?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-24292f?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-24292f?style=flat-square&logo=sqlite&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-24292f?style=flat-square&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-24292f?style=flat-square&logo=fastapi&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-24292f?style=flat-square)
![Git](https://img.shields.io/badge/Git-24292f?style=flat-square&logo=git&logoColor=white)
