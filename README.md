# Carbon-Emission-Analysis
Overview
This project explores the relationship between global temperature changes and CO₂ concentrations over time. Leveraging datasets of historical temperature records and CO₂ emissions, the analysis uncovers trends, patterns, and correlations, providing insights into climate dynamics. Advanced data visualization, statistical modeling, and machine learning techniques are applied to quantify and interpret these relationships.

The repository includes code for preprocessing, statistical analysis, trend identification, clustering, and predictive modeling to assess the potential impact of CO₂ levels on global temperatures.

Features
1. Data Analysis and Preprocessing
Datasets used:
Temperature change data (time-series format with global averages).
CO₂ concentration data (monthly and annual averages).
Cleaning and transforming raw data for exploratory analysis.
Generating descriptive statistics to summarize data variability.
2. Insights Derived
Statistical Analysis
Temperature Stats:
Mean, Median, and Variance of global temperature changes.
CO₂ Stats:
Mean, Median, and Variance of CO₂ concentrations.
Correlation Analysis
Strong correlation identified between CO₂ concentrations and global temperature changes using:
Pearson Correlation Coefficient.
Spearman Rank Correlation.
Trend Analysis
Temperature Change: Increasing trend over decades with a slope derived from linear regression.
CO₂ Concentration: Steady rise over time, closely aligned with temperature trends.
3. Data Visualizations
Time-Series Analysis:
Visualized temperature changes and CO₂ concentrations over time with clear upward trends.
Correlation Heatmap:
Highlighted significant correlations between CO₂ levels and temperature changes.
Scatter Plot:
Demonstrated a positive relationship between CO₂ concentration and temperature changes.
Seasonal Variations:
Monthly variations in CO₂ concentrations analyzed for periodic patterns.
4. Machine Learning Insights
Clustering Analysis:
Applied K-Means clustering to group years based on similar climate patterns.
Defined clusters:
Moderate Temp & CO₂
High Temp & CO₂
Low Temp & CO₂
Predictive Modeling:
Developed a simple linear regression model to predict temperature changes based on CO₂ levels.
Simulated "what-if" scenarios for temperature changes with ±10% and ±20% variations in CO₂ levels.
5. Advanced Statistical Analysis
Granger Causality Test:
Investigated causality between CO₂ concentration and temperature changes, confirming the significant influence of CO₂ on temperature trends.
Lagged Effect Analysis:
Modeled the lagged impact of CO₂ levels on temperature changes using multivariate regression.
6. Key Results
A consistent upward trend in global temperatures aligns with rising CO₂ concentrations.
Significant correlation (Pearson: 0.85, Spearman: 0.83) between CO₂ and temperature.
Clustering identified periods of high, moderate, and low climate impact, emphasizing how CO₂ variations affect global climate dynamics.
Predictive simulations demonstrated temperature sensitivity to CO₂ level changes, with a 10% increase in CO₂ causing a significant rise in global temperatures.
7. Visual Summary
The repository includes interactive Plotly visualizations for trend analysis, correlations, clustering, and predictive insights.

How to Use
Clone the repository:

Copy code
git clone https://github.com/raj07a/climate-analysis.git  

Install dependencies:

Copy code
pip install -r requirements.txt  

Run the notebook or scripts for analysis:
Temperature and CO₂ time-series analysis.
Clustering and predictive simulations.
