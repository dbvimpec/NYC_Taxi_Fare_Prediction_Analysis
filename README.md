# Business Understanding

New York City taxi drivers need accurate fair predictions to optimize price strategies and improve customer experience. For this project we are going to develop machine learning models to predict taxi fares based on trip characteristics. We will identify key factors influencing fare prices

# Data Understanding

You're importing Taxi Trip Data NYC data set from Kaggle. The data set has over 83,000 rows and 20 feature. 12/14/20 - 08/01/2021 is the time period captured in this data set

## Data Preparation

Getting data ready for analysis by cleaing the data set and set up some feature engineering. Datetime features will be created, removal of unnecessary columns and then preparing the featured columns and target for analysis. A preprocessing pipeline will also be created.

# Exploratory Data Analysis

![1_Fare_vs_Trip_Distance](https://github.com/user-attachments/assets/69bf6eb2-9a45-44de-ab0d-04c4ab73b895)
![2_fare_by_hour_of_day](https://github.com/user-attachments/assets/72e56b7d-d6ff-4acb-8497-8faabc7c0deb)
![3_ fare_by_day_of_week](https://github.com/user-attachments/assets/80048fcd-3d2f-466d-89ed-48173d635b3e)
![4_trip_duration_vs_fare_1](https://github.com/user-attachments/assets/cda3fee4-5690-46dd-be3a-ce49dd50c3e3)
![5_trip_duration_vs_fare_2](https://github.com/user-attachments/assets/2e7a54ba-9d5f-4bbe-bcc1-f36fd53f6f3c)
![6_SHAP_ feature_importance_random_forest_1](https://github.com/user-attachments/assets/6942dbcb-9231-4d58-9795-2a20eae4052f)
![7_SHAP_ feature_importance_random_forest_2](https://github.com/user-attachments/assets/045f9e0e-4110-40da-8f76-e50cb90cbd02)
![8_SHAP_ feature_importance_random_forest_2a](https://github.com/user-attachments/assets/ed41390e-63f3-49f2-b256-aacb54344cc3)
![9_ prediction_analysis_actual vs_predicted_fares](https://github.com/user-attachments/assets/cfc91892-a56f-4374-bf33-22b3cce8e998)


# Conclusion

We've successfully implemented an end-to-end machine learning pipeline for New York City tax fair predictions. The project addresses the business need for accurate fair estimation to improve transparency and customer satisfaction. The original data site was 83,000+ and after cleaning we were able to reduce it down to 68,000+. Our target was the fare column, and the key features were a distance, duration, time patterns. The Random Forest model was the model that performed the best. Were able to predict that $27.76 would be the average fare. Short trip or rush hour fares were predicted at $21.14, long trips were predicted at $40.85 and weekend trips were predicted at $24.81.

## Limitations

Some of the limitations that we encountered is that the data set is limited to 12/14/20 - 08/01/2021 for the NYC market only. It's also during the pandemic. There aren't any seasonal variations. We are geographic location limitations, because the data was unclear on specific areas/locations. Traffic patterns were not captured either. Airport surcharges pricing was missing from the data as well.

## Recommendations

To get a better picture, it would be good to integrate New York City TLC zone data for location based features and adding weather data from New York City weather APIs. Develop real time data pipeline for live predictions. Develop multiple city prediction capabilities with advanced analytics.

## Next Steps

Next steps would be to implement continuous model monitoring. Set up automated retraining pipeline. Develop fallback models. Data validation practices should be used.
