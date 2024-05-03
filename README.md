# Seoul Bike Sharing Demand Prediction

## Project Summary
This Seoul Bike Sharing Demand Prediction project aims to forecast the demand for bike-sharing based on historical data. The dataset used contains information from a bike-sharing system including date, hour, weather conditions, temperature, and the number of bikes rented.

## Project Goal 
The goal of this project is to build a predictive model that accurately estimates bike rental demand for any given hour. The model is evaluated based on its accuracy in predicting the number of bikes rented during a specific hour.

## Dataset Overview
- The dataset contains rental bike information with 8760 observations and 14 variables.
- Variables include Date, Rented Bike Count, Hour, Temperature (°C), Humidity (%), Wind speed (m/s), Visibility (10m), Dew point temperature, Solar Radiation, Rainfall (mm), Snowfall (cm), Seasons, Holiday, and Functioning Day.
- Data preprocessing steps include transforming the Date feature to datetime64 format, handling outliers, and creating new variables for day, month, and year.
- Exploratory data analysis revealed insights such as seasonal trends, holiday impacts, and time-of-day usage patterns.

## Modeling Approach
- Descriptive statistics, visualizations, and feature engineering techniques were used for data exploration.
- Machine learning models including linear regression, Lasso (L1), Ridge (L2), ElasticNet, Decision Tree regressors, Random Forest, and XGBoost regression were implemented.
- Feature importance analysis highlighted the significant influence of Functioning Days, Rainfall, and Seasons on the XGBoost model.
- SHAP (SHapley Additive exPlanations) was used to explain the XGBoost model's predictions.

## Problem Statement
The prediction of bike rental demand is crucial for optimizing the supply of rental bikes in urban cities. By accurately forecasting the required bike count at each hour, cities can ensure a stable supply of rental bikes, thereby enhancing mobility comfort for the public.

## Acknowledgments
The dataset[SeoulBikeData.csv] used in this analysis is sourced from [https://data.mendeley.com/datasets/zbdtzxcxvg/1] and is publicly available.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Contact
For any questions or feedback, please contact [sayak.kr.dutta1@gmail.com].

