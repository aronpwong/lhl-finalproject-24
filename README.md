# Impact of Air Quality on MTA Ridership in NYC 🗽🍎
Understanding the connection between public transportation and the air we breathe is crucial because it directly impacts our daily lives and health. Public transportation, like buses and subways, can help reduce the number of cars on the road, which in turn can lower pollution levels. Cleaner air means fewer health problems, especially for children, the elderly, and those with respiratory conditions.

### Problem Statement:
*"How does air quality impact public transportation usage in New York City, and what implications does this have for city planning and public health without losing efficacy?"*

### Objective:
To investigate the relationship between air quality and MTA ridership to provide insights for improving public health and sustainable city planning.

## Project Structure
### **Project Planning and Definition**
**Define Objectives:** 

1. Clearly define the goals of the project
2. Understand the data and computational resources needed, and set timelines for project milestones.

### **Data Collection and Preparation**
**Data Sourcing:**

1. Collect relevant datasets
2. Data Cleaning: Handle missing values, correct errors, and ensure consistency across datasets.
3. Data Integration: Merge datasets based on common attributes to create a unified dataset for analysis.

### **Exploratory Data Analysis (EDA)**

**Descriptive Statistics:** Calculate summary statistics for key variables to understand their distributions and identify any anomalies.
**Correlation Analysis:** Examine relationships between subway ridership and pollution levels using correlation coefficients.
**Visualization:** Create scatter plots, heatmaps, and histograms to visually explore patterns and relationships in the data.
**Outlier Detection:** Identify and analyze outliers in ridership and pollution data, which could indicate special events or anomalies.

### **Modeling and Prediction**

**Time Series Analysis:**

**SARIMA Modeling:** Fit SARIMA models to forecast subway ridership based on historical trends and seasonality.

**Machine Learning Models:**

**Random Forest:** Train a Random Forest model to predict ridership based on pollution levels and other features.
**XGBoost:** Train and compare an XGBoost model, focusing on feature importance and model accuracy.
**Model Evaluation:** Assess model performance using metrics like MAE, RMSE, and R². 

### Key Findings 
**Understanding the Relationship Between Ridership and Pollution:**
The analysis revealed a moderate positive correlation between subway ridership and traffic-related pollutants like NO2 and CO. This suggests that increased pollution levels, often associated with higher traffic congestion, correspond to higher public transportation usage.
This relationship indicates that optimizing public transportation routes to cater to areas with high pollution could potentially reduce the number of private vehicles on the road, thus lowering overall emissions.

**Seasonality and Temporal Patterns in Ridership:**
Ridership shows clear weekly and seasonal patterns, which are critical for optimizing service schedules. The SARIMA model effectively captured these patterns, providing a reliable tool for short-term forecasting.
By aligning service levels with these patterns, NYC can optimize resource allocation, reduce operational costs, and minimize unnecessary emissions from underutilized services.

**Handling Anomalies and High-Ridership Events:**
The detection of outliers in the ridership data, corresponding to special events or holidays, underscores the need for adaptive and flexible routing strategies. These strategies ensure that the transportation system can handle sudden increases in demand without compromising service quality or increasing emissions.
Predictive models can help in anticipating these events, allowing NYC to adjust service levels proactively.

**Predictive Modeling for Informed Decision-Making:**
The SARIMA model proved to be a valuable tool for forecasting ridership based on historical trends and seasonality, making it ideal for short-term planning and scheduling.
The Random Forest model offered insights into the complex interactions between pollution levels, temporal factors, and ridership. This model is useful for scenarios where multiple variables need to be considered simultaneously, such as when planning routes that balance demand, service efficacy, and environmental impact.


## Final Thoughts

This project demonstrates that data science can significantly contribute to optimizing public transportation in NYC, with the potential to reduce carbon emissions, improve air quality, and maintain or even enhance service efficacy. By leveraging predictive models and data-driven insights, NYC can make informed decisions that promote sustainable urban mobility and better meet the needs of its residents.

These insights and models provide a foundation for more sustainable transportation planning, aligning with broader environmental goals and ensuring that public transportation remains a reliable and efficient option for city dwellers.

### Challenges

* **Data Availability and Quality:**
Incomplete or Missing Data: Some datasets may have missing values or incomplete records, which can hinder analysis and model accuracy. For example, gaps in pollution data or ridership statistics can lead to less reliable correlations and predictions.

* **Multifactorial Influences:**
Subway ridership is influenced by a wide range of factors beyond pollution, such as weather, socio-economic conditions, and public events. Accurately modeling these complex interactions is challenging, particularly when data on all relevant factors is not available.

* **Lag in Data Availability:**
There may be delays in obtaining or processing real-time data, which can affect the timeliness and accuracy of model predictions. This can be especially problematic for dynamic adjustments to public transportation routes.
  
### Recommendations

* **Targeting Pollution Hotspots:**
Prioritize route optimization in areas with high NO2 and CO levels to reduce emissions and improve air quality.

* **Focus on Income and Population Density:** 
While direct correlations weren't established, it's likely that neighborhoods with lower incomes and higher population densities rely more on public transport. Optimizing routes in these areas can enhance service effectiveness and ensure equitable access.

* **Balancing Service and Environmental Goals:** 
The challenge is to maintain or improve public transport services while reducing emissions. Data science can help by identifying under-utilized routes or suggesting alternative modes of transport.

* **Dynamic Service Adjustments:**
Use predictive models to adjust service levels in real-time, ensuring resources are allocated efficiently based on predicted ridership and pollution levels.

* **Integrate Real-Time Data:** 
Incorporate real-time traffic, air quality, and event data into predictive models for more responsive and accurate transportation adjustments.

* **Continuous Monitoring and Feedback:** 
Establish a feedback loop through continuous monitoring of pollution and ridership, allowing data to inform real-time decisions, such as increasing public transport options when air quality deteriorates.


## Future Explorations

**Short Term Planning**
1. Incorporate Additional Data Sources
2. Refine and Expand Predictive Modeling
3. Implement Real-Time Forecasting and Adjustment
4. Optimization of Service Routes
5. Enhanced Evaluation and Validation

**Long Term Planning**
1. Stakeholder Engagement and Implementation
2. Scalability and Deployment
3. Continuous Monitoring and Feedback Loop
