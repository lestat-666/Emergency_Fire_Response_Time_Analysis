# EMERGENCY_RESPONSE_TIME_PREDICTION - SAN_FRANCISCO_FIRE_DEPARTMENT

## Predictive modeling of emergency response times using machine learning and geospatial analysis across 152,384 emergency incidents to optimize service delivery.

## Project Overview
This project develops a comprehensive machine learning pipeline to predict San Francisco Fire Department response times using 2022 emergency dispatch data. The system integrates large-scale data processing, geospatial analysis, and multiple predictive algorithms to understand factors affecting emergency response efficiency and provide actionable insights for service optimization.

## Key Findings 
- **Data Processing Scale**: Successfully processed 2.6GB dataset (20+ years) focusing on 152,384 unique emergency records across 44 fire stations
- **Geospatial Insights**: Strong correlation identified between emergency call frequency and population density; highest volumes in Tenderloin, Mission, and Bayview neighborhoods
- **Temporal Patterns**: Emergency calls peaked during 10-17h daily with 35% longer response times during peak periods and weekend midnight hours
- **Predictive Performance**: Best model (Gradient Boosting) achieved R² = 0.49, MAE = 201 seconds for regression; 24-28% accuracy for categorical classification
- **Counterintuitive Discovery**: Driving distance showed minimal correlation (0.01) with response times, indicating operational factors dominate over geographic proximity
- **Policy Validation**: Life-threatening emergencies met San Francisco's 10-minute response target approximately 90% of the time

## Technical Stack
**Data Processing**: Python, pandas, NumPy, Stata  
**Machine Learning**: Scikit-learn, Random Forest, Gradient Boosting, K-Nearest Neighbors, SVM  
**Geospatial Analysis**: GeoPandas, OSRM Routing API, Plotly/Mapbox  
**APIs**: Open Source Routing Machine (OSRM), Google Geocoding API  
**Web Scraping**: BeautifulSoup, requests  
**Visualization**: matplotlib, seaborn, Plotly  
**Cloud Platform**: Google Cloud Platform (GCP)  

## Authors
Anastasiia Golovchenko et al.
