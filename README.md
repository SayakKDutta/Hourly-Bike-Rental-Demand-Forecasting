# Seoul Bike Sharing Demand Prediction

## Project Summary
This Seoul Bike Sharing Demand Prediction project aims to forecast the demand for bike-sharing based on historical data. The dataset used contains information from a bike-sharing system including date, hour, weather conditions, temperature, and the number of bikes rented so to ensure a stable supply of rental bikes, thereby enhancing mobility comfort for the public.


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

## Conclusion

- Customers tend to rent motorcycles equally across all seasons.
- Rental bike usage is highest during functional hours and least during the night.
- Bike rentals are popular throughout the year, with a notable increase in 2018 compared to 2017.
- Rental bike usage peaks during office commute times in the morning and evening.
- Humidity levels between 10% and 18% are optimal for bike rentals.
- Dew point temperatures ranging from 12°C to 18°C are ideal for rental bike usage.
- Solar radiation, rain, and snowfall have varying effects on rental bike usage.
- The first 10 days and the last 15 days of the month see the highest rental bike usage.
- June and October are the peak months for rental bike usage.
- Visibility exceeding 1750m increases rental bike usage.
- Rental bike usage is higher during summer and autumn compared to winter.
- Even on non-holiday days, rental bike usage remains consistent.
- Most rental bikes are used during their functional hours.

Overall, these insights can help in understanding customer preferences and optimizing bike rental services.


## Acknowledgments
The dataset [SeoulBikeData.csv](SeoulBikeData.csv) used in this analysis is sourced from [https://data.mendeley.com/datasets/zbdtzxcxvg/1] and is publicly available.

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

