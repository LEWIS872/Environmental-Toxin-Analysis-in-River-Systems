# TItle
Environmental Toxin Analysis in River Systems

# Project Overview
This project analyses environmental toxin data across major river systems to uncover patterns, trends, and risk factors affecting water quality. The analysis was conducted as part of an environmental  data initiative at EcoGuard, a non-profit organisation focused on protecting water resouces.
The objective is to support data-driven environmental monitoring and policy development by identifying high-risk rivers, understanding toxin behaviour, and exploring relationships between environmental variables.

# Objectives
1. Analyse toxin levels across different river systems.
2. Identify trends in pollution levels  over time.
3. Detect high-risk rivers with elevated toxin concetrations.
4. Examine relationship between pH levels and toxin levels.
5. Explore patterns to support environmental decision-making.

# Tools & Technologies
Python|Pandas|Numpy|Matplotlib|Seaborn|SciPy(Statistical testing)|Scikit-learn(Linear Regression)|JupyterNotebook

# Dataset Description
The dataset contains environmental measurements collected over a five-year period, including:
1. Toxin levels(Lead. Mercury, Arsenic).
2. Water quality indicators(pH level, Dissolved Oxygen).
3. Nutrients levels(Nitrate, Phosphate).
4. Temperature
5. River system identifiers.
6. Time(Date)

# Data Preparation
1. Checked for missing values across all variables.
2. Imputed missing values using column means for numerical data.
3. Converted the Date column to datetime format.
4. Ensuren all toxin variables were in numeric format for analysis.

# Exploratory Data Analysis
Average Toxin Levels
1. Lead : 3.01
2. Mercury : 0.60
3. Arsenic : 3.60

# Most polluted Rivers (Lead Levels)
1. Yangtze (highest)
2. Mississippi
3. Nile
4. Danube
5. Amazon(Lowest among top group)
Indicates significant variation in pollution levels across river systems.

# Toxin Trends Over Time
1. Lead levels fluctuates over time  across river systems.
2. Patterns suggest possible seasonal variation and pollution events.

# Correlation Analysis
1. Strong relationships observed between environmental variables.
2. pH level shows a positive relationship  with Lead concentration.
This suggests  environmental conditions influence toxin behaviour.

# Statistical Analysis
T-test (Amazon Vs Nile)
1. T-statistic : -20.24
2. P-value : 1.34e^-67
This is a Statistically significant difference in Lead levels between the Amazon and Nile rivers.

# Linear Regression (pH Vs Lead)
1. Coefficient : 0.80
2. Intercept :-2.89
This indicates a positive relationship between pH levels and Lead concentration.

# Key Findings
1. Significant differences in toxin levels exist across river systems.
2. Yangtze and Mississippi rivers show higher pollution levels.
3. Lead levels vary over time, suggesting dynamic environmental conditions.
4. Strong statistical evidence confirms differences between river systems.
5. pH levels are positively associated with Lead concentration.

# Environmental Implications
The findings highlight critical environmental concerns:
1. Rivers with elevated toxin levels pose ecological and public health risks.
2. Environmental factors such as pH play a role in toxin concentration.
3. Pollution is not uniform and requires targeted interventions.

These insights emphasize the need for data-driven environmental monitoring and policy development.


# Recommendations
1. Prioritise monitoring and clean-up efforts in highly polluted rivers (e.g Yangtze and Mississippi, Nile).
2. Investigate environmental factors such as pH as drivers of toxin variation.
3. Implement continuous monitoring systems for early detection of pollution spikes.
4. Support environmental policies with statistical and data-driven evidence.

# Conclusion
This project provides a comprehensive analysis of toxin levels across major river systems. The results reveal significant variation in pollution levels, with some rivers exhibiting consistently higher toxin concentrations.
Statistical analysis confirms that these differences are not due to chance, while regression analysis highlights the influence of environmental conditions such as pH on toxin behaviour.
Overall, the findings underscore the importance of targeted enviromental monitoring, informed policy intervention, and efficient resource allocation to address pollution in high-risk river systems.

