# country-clustering-analysis-unsupervised
Project Overview

This project focuses on segmenting countries based on their socio-economic and health indicators using clustering techniques.
The goal is to help an international NGO identify countries that need urgent support and allocate resources effectively.

🎯 Problem Statement

An international NGO has limited funds and resources and cannot support all countries equally.

The challenge is to:

Identify countries that need immediate help

Group countries based on development level

Support data-driven decision making

📊 Dataset Information

Dataset Name: Country-data.csv

Source: Public Dataset

Link: https://1drv.ms/x/c/a48c01fec5c3c6a6/IQDuwhfW9U-9Qp2FOYpLtiJ_Adfen4dtPsiOS7YEAUqp4ho?e=6qRwTu

🔑 Features

country – Country name

child_mort – Child mortality rate

exports – Export percentage of GDP

health – Health spending (% GDP)

imports – Import percentage of GDP

income – Net income per person

inflation – GDP growth rate

life_expec – Life expectancy

total_fer – Fertility rate

gdpp – GDP per capita

⚙️ Technologies Used

Python 

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

🔄 Project Workflow

Data Understanding

Data Preprocessing

Feature Scaling

Exploratory Data Analysis (EDA)

Feature Selection

K-Means Clustering

Finding Optimal Clusters (Elbow Method)

Cluster Profiling

Visualization

Insights & Recommendations

📈 Clustering Approach

Used K-Means algorithm for clustering

Applied feature scaling to normalize data

Determined optimal clusters using:

Elbow Method

Silhouette Score

📊 Results

Countries were grouped into 3 clusters:

🌟 Developed Countries

High income

High life expectancy

Low child mortality

⚙️ Developing Countries

Moderate economic and health indicators

⚠️ Underdeveloped Countries

Low income

High child mortality

Low life expectancy

💡 Insights

Countries with low income & high mortality need urgent attention

Developed countries show strong economic and health conditions

Clear separation of countries based on development level

✅ Recommendations

Focus funding on underdeveloped countries

Improve:

Healthcare

Education

Economic opportunities

Support developing countries for long-term growth

⚠️ Limitations

Limited dataset features

Clustering depends on selected K value

External factors (politics, environment) not included

🏁 Conclusion

This project demonstrates how clustering techniques can help in:

Identifying country groups

Supporting NGOs in decision-making

Efficient allocation of resources
