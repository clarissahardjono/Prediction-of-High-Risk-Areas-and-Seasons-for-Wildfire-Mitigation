# Prediction-of-High-Risk-Areas-and-Seasons-for-Wildfire-Mitigation
This project leverages machine learning models to predict high-risk areas and seasons for wildfires in Portugal. Using datasets containing wildfire occurrences and daily weather data. XGBoost achieved 96-97% accuracy, providing data-driven insights to improve wildfire prevention and resource allocation.

## Key Features
- **Machine Learning Models**: XGBoost, Random Forest, Decision Tree, and Multivariate Regression.
- **Data Sources**:
  - **Forest Fires Dataset** (Kaggle) – Includes wildfire occurrences and climate indices.
  - **Portugal Weather Dataset** (Kaggle) – Daily weather data in Portugal between 2022 and 2023.
- **Feature Engineering**: Created new features like dryness index and temperature-wind interactions.
- **Data Balancing**: Applied **SMOTE** to handle class imbalance.
- **Hyperparameter Optimization**: Used GridSearchCV for tuning models.
- **Performance**: XGBoost achieved **96-97% accuracy**, outperforming other models.

## Project Goals
- **Early detection of wildfire risk** to support decision-makers.
- **Reduce environmental, economic, and human losses** caused by wildfires.
- **Improve resource allocation** based on predictive insights.

## Datasets
- **Forest Fires Dataset**: [Kaggle Link](https://www.kaggle.com/datasets/elikplim/forest-fires-data-set)
- **Portugal Weather Dataset**: [Kaggle Link](https://www.kaggle.com/datasets/saeedaghasoleimani/portugal-weather-from-2022-08-01-to-2023-08-01)

## Findings & Recommendations
- **Wildfire risks are highest under conditions of high temperature, low humidity, strong winds, and minimal rainfall.**
- **Preventive efforts should be prioritized in peak-risk months** by allocating resources efficiently and deploying firefighting personnel in high-risk areas.
- **A data-driven approach is essential** for wildfire prevention, requiring continuous climate monitoring and regular updates.
- **Integrating satellite data with real-time climate information** can improve prediction accuracy and proactive response.
- **Collaboration between governments, environmental agencies, and researchers** can enhance wildfire management strategies.
- **Long-term sustainability efforts** should focus on forest restoration, ecosystem protection, and climate change mitigation.

## Limitations & Future Improvements
- **Geographical Limitation**: The model is trained specifically on wildfire data from Portugal, limiting its applicability to other regions.
- **Limited Features**: The dataset lacks important variables like solar radiation, soil moisture, and human activity data, which could improve prediction accuracy.
- **Computational Cost**: XGBoost, while highly accurate, requires significant computational resources, making real-time deployment challenging.
- **Class Imbalance**: Despite using SMOTE for balancing, model performance could still be improved for minority-class predictions.
- **Future Improvements**:
  - Incorporate **satellite data** for more comprehensive climate monitoring.
  - Expand the dataset to include **global wildfire data** for broader applicability.
  - Enhance **feature engineering** by integrating additional climate and environmental variables.
  - Optimize the model for **real-time predictions** with reduced computational complexity.

