# Life-Expectancy-Analysis
# About Dataset
 # Context
 Although there have been a lot of studies undertaken in the past on factors affecting life expectancy considering demographic variables, income composition and mortality rates. It was found that affect of immunization and human development index was not taken into account in the past. Also, some of the past research was done considering multiple linear regression based on a data set of one year for all the countries. Hence, this gives motivation to resolve both the factors stated previously by formulating regression model based on mixed effects model and multiple linear regression while considering data from a period of 2000 to 2015 for all the countries. Important immunization like Hepatitis B, Polio and Diphtheria will also be considered. In a nutshell, this study will focus on immunization factors, mortality factors, economic factors, social factors and other health related factors as well. Since the observations in this dataset are based on different countries, it will be easier for a country to determine the predicting factor which is contributing to lower value of life expectancy. This will help in suggesting a country which area should be given importance in order to efficiently improve the life expectancy of its population.
 
# Content
 
The project relies on accuracy of data. The Global Health Observatory (GHO) data repository under World Health Organization (WHO) keeps track of the health status as well as many other related factors for all countries The data-sets are made available to public for the purpose of health data analysis. The data-set related to life expectancy, health factors for 193 countries has been collected from the same WHO data repository website and its corresponding economic data was collected from United Nation website. Among all categories of health-related factors only those critical factors were chosen which are more representative. It has been observed that in the past 15 years , there has been a huge development in health sector resulting in improvement of human mortality rates especially in the developing nations in comparison to the past 30 years. Therefore, in this project we have considered data from year 2000-2015 for 193 countries for further analysis. The individual data files have been merged together into a single data-set. On initial visual inspection of the data showed some missing values. As the data-sets were from WHO, we found no evident errors. Missing datawas handled in R software by using Missmap command. The result indicated that most of the missing data was for population, Hepatitis B and GDP. The missing data were from less known countries like Vanuatu, Tonga, Togo, Cabo Verde etc. Finding all data for these countries was difficult and hence, it was decided that we exclude these countries from the final model data-set. The final merged file(final dataset) consists of 22 Columns and 2938 rows which meant 20 predicting variables. All predicting variables was then divided into several broad categories: Immunization related factors, Mortality factors, Economical factors and Social factors.
 
 # Acknowledgements

The data was collected from WHO and the United Nations website with the help of Deeksha Russell and Duan Wang.

# Inspiration

The data-set aims to answer the following key questions:

 1. Do various predicting factors which have been chosen initially really affect the Life expectancy? What are the predicting variables actually affecting life expectancy?
 2. Should a country having a lower life expectancy value(<65) increase its healthcare expenditure in order to improve its average lifespan?
 3. How does Infant and Adult mortality rates affect life expectancy?
 4. Does Life Expectancy has positive or negative correlation with eating habits, lifestyle, exercise, smoking, drinking alcohol etc.
 5. What is the impact of schooling on the lifespan of humans?
 6. Does Life Expectancy have positive or negative relationship with drinking alcohol?
 7. Do densely populated countries tend to have lower life expectancy?
 8. What is the impact of Immunization coverage on life Expectancy?

Analyzing life expectancy data involves examining various factors that may affect life expectancy rates in different countries. For a finance analyst project, we can approach this analysis by looking at economic indicators, healthcare spending, and other socio-economic factors that might influence life expectancy. Here, I'll outline a basic life expectancy analysis project using Python, incorporating data collection, cleaning, EDA (Exploratory Data Analysis), and  some basic statistical analysis.

Example: You can get the basic idea how you can create a project from here Step-by-Step Life Expectancy Analysis.

 1. Data Collection
 For this analysis, we'll use a publicly available dataset. Let's use the "Life Expectancy Data" from the World Health Organization (WHO), which you can find on Kaggle or directly from WHO's repository.
 2. Data Cleaning
 We'll clean the data by handling missing values, duplicates, and any anomalies.
 3. Exploratory Data Analysis (EDA)
 We'll perform EDA to understand the distribution and relationships in the data.
 4. Statistical Analysis and Visualization
 We'll conduct statistical tests and visualize the relationships between life expectancy and various economic indicators.

# 📋 Project Summary:

In this project, I analyzed a global life expectancy dataset to identify the key factors that influence human longevity across countries and over time.

I started with:
- Cleaning the data and handling missing values
- Encoding categorical variables like 'Status' for modeling
- Visualizing distributions, trends, and relationships between features

Then I applied machine learning models — Random Forest and XGBoost — to predict life expectancy based on various socioeconomic and healthcare indicators.

I also performed advanced visualizations including:
- Choropleth map to show global life expectancy differences
- Violin plot comparing education levels by development status
- Pairplot of key predictors for multivariate pattern discovery
- Residual plot to analyze model error distribution
- What-if scenario simulation showing impact of increased schooling
- Actual vs predicted scatter plot to validate model alignment
- Model performance comparison table (R² and RMSE)

Throughout the analysis, I focused on clarity, interpretability, and actionable insights.

# 📌 Project Conclusion:

- The models performed well, with R² scores above 0.90, showing strong predictive power.
- Features like Schooling, Immunization, Income Composition, and Health Expenditure were among the most important drivers of life expectancy.
- Developed countries consistently have higher life expectancy, but the gap is slowly narrowing.
- Visualization tools like heatmaps and animated scatter plots helped highlight disparities and trends over time.
- Advanced error analysis (residual plots) confirmed model reliability.
- The project clearly shows that improving education and healthcare access can lead to significant gains in national life expectancy.

This conclusion not only validates the effectiveness of predictive modeling, but also supports data-driven policy recommendations.

# 🚀 Future Enhancements:

To expand the business impact of this project, I propose the following enhancements:

1. 📈 Build Time-Series Forecasting Models  
   Predict life expectancy for upcoming years (e.g., 2030, 2040) using historical trends. This can help governments and health organizations plan future investments.

2. 🌍 Add Geopolitical & Environmental Features  
   Include additional variables like pollution levels, healthcare infrastructure, climate change indicators, and public policy metrics for deeper analysis.

3. 🧠 Develop a Machine Learning Dashboard  
   Deploy this project as an interactive web dashboard using tools like Streamlit or Power BI, where stakeholders can explore life expectancy by country, year, and feature impact dynamically.

4. 🔄 Real-time Data Integration  
   Link the model to open APIs or UN health databases to update results regularly and support real-time decision-making for international agencies.

5. 🎯 Integrate Policy Simulator  
   Allow stakeholders to simulate interventions (e.g., increasing schooling by 2 years) and view projected changes in life expectancy per country or region.

These enhancements would turn this into a scalable, data-driven tool for global health forecasting, investment planning, and strategy development.
