# **Forecasting Monthly Consumer Price Index (CPI) in the Philippines**

A collaborative project developed to create an accurate and interpretable forecast of Philippine monthly CPI based on historical data for 2025.  

**Disclaimer: This project was created as a requirement for the course DS1321 - Time Series Analysis and Stochastic Processes.** 

*Project Duration: February - May 2026*

# Introduction
Consumer Price Index or CPI is a key economic indicator that reflects price movements in essential categories (e.g. food, transportation, housing, and utilities). CPI specifically measures the average change over time in the prices paid by consumers for a **representative basket of consumer goods and services**. Although CPI is used to compute for inflation, inflation monitors the **overall increase in prices of goods and services** in an economy over time. 

## CPI Baseline Years
In the Philippines, there are multiple baseline years set according to when the economy is considered most stable. According to the [Bangko Sentral ng Pilipinas](https://www.bsp.gov.ph/SitePages/Statistics/Prices.aspx?TabId=1) (BSP), the baseline years in the Philippines were 2000, 2006, 2012, and 2018. However, the [Philippine Statistics Authority](https://business.inquirer.net/505117/ph-to-adjust-inflation-gdp-baseline-starting-2026) (PSA) recently stated that it will rebase to 2023. 

## Goal and Main Question
Multiple baseline years are common, and it is done to ensure that the baseline is till a representative of the economy. However, how do we understand CPI better so that we can forecast and predict future CPI using the right baseline? With this, the project aims to develop an accurate and interpretable forecast of Philippine monthly CPI based on historical data for 2025. 

# Data Source and Collection
The data used in this study comes from the [World Bank's Global Database of Inflation](https://www.worldbank.org/en/research/brief/inflation-database), which aggregates CPI data from OECD.Stat, the IMF World Economic Outlook, the ILO, and national statistical offices. For the Philippines, the underlying source is the PSA. The dataset covers major household consumption categories: food, housing, transport, health, education, recreation, and others. One important note is that the World Bank database does not explicitly tag a baseline year in its variable naming. We verified separately that the Philippine series aligns with the PSA's 2018 base year, which is the current official baseline.

# Machine Learning Models Used
1. ARIMA
2. SARIMA
3. Simple RNN
4. LSTM
5. Transformer
6. CNN

*Note. Using deep learning models were a requirement for the course*

# Repository Content
- In the datasets folder, it contains five (5) csv files containing CPI data from the Philippines and four (4) other Southeast Asian countries. This was created for the Exploratory Data Analysis (EDA) portion.
- In the notebooks folder, it contains one jupyter notebook that contains everything from EDA to Machine Learning.
- In the documents folder, it contains the written report for this project, complete with an in-depth analysis of the results and suggestions. 

# License 
This repository is licensed under the MIT License.  

If you use or adapt any part of this work, please provide attribution by mentioning the authors: Anna Cruz, Dan  Gatus, and Marielle Tango.
