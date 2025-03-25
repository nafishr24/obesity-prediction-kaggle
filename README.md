# Predicting Obesity Levels Using Machine Learning

Obesity is a chronic complex disease defined by excessive fat deposits that can impair health. It increases the risk of type 2 diabetes, heart disease, certain cancers, and can affect bone health, reproduction, and overall quality of life, including sleep and mobility.

The diagnosis of overweight and obesity is typically made by measuring weight and height to calculate the body mass index (BMI): weight (kg)/height² (m²). BMI serves as a surrogate marker of fatness, and additional measurements, such as waist circumference, can further aid in diagnosing obesity.

## Project Overview

This project aims to analyze and classify a person's obesity level based on various health and lifestyle factors. Using a dataset with features such as weight, height, eating habits, exercise routines, and more, this project applies exploratory data analysis (EDA) and several machine learning algorithms to gain deeper insights into obesity.

## Machine Learning Models Used

To classify obesity levels, this project utilizes three machine learning models:
- **Logistic Regression**: Chosen for its simplicity and interpretability. It is effective for binary and multiclass classification problems, making it a good baseline model.
- **Random Forest**: Selected for its ability to handle non-linearity, reduce overfitting through ensembling, and provide feature importance insights.
- **XGBoost**: Used due to its high performance, efficiency, and ability to handle imbalanced datasets, making it an excellent choice for improving accuracy and robustness.

## Dataset Information

This dataset helps estimate obesity levels based on eating habits, family history, and physical condition. It includes data from individuals in Mexico, Peru, and Colombia, covering 16 lifestyle and health-related features with 2111 records. The labels classify obesity levels, ranging from underweight to different obesity types.

Most of the data was generated using synthetic techniques, while some were collected directly from users through a web platform. It is useful for classification, regression, and clustering tasks. The dataset was obtained from **Kaggle**, a platform providing datasets for machine learning and data science projects.

## Column Descriptions
- **Gender** – Male or Female.
- **Age** – The person’s age in years.
- **Height** – Height in meters.
- **Weight** – Weight in kilograms.
- **family_history_with_overweight** – Whether the person has a family history of being overweight (yes/no).
- **FAVC** – If the person frequently consumes high-calorie foods (yes/no).
- **FCVC** – Frequency of vegetable consumption (scale from 1 to 3).
- **NCP** – Number of main meals per day.
- **CAEC** – Frequency of consuming food between meals (Never, Sometimes, Frequently, Always).
- **SMOKE** – Whether the person smokes (yes/no).
- **CH2O** – Daily water intake (scale from 1 to 3).
- **SCC** – If the person monitors their calorie intake (yes/no).
- **FAF** – Physical activity frequency (scale from 0 to 3).
- **TUE** – Time spent using technology (scale from 0 to 3).
- **CALC** – Frequency of alcohol consumption (Never, Sometimes, Frequently, Always).
- **MTRANS** – Main mode of transportation (Automobile, Bike, Motorbike, Public Transportation, Walking).
- **NObeyesdad** – Obesity level (Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, Obesity Type III).

## Conclusion
Based on the evaluation of the three models, **XGBoost** outperforms both **Logistic Regression** and **Random Forest**, achieving the highest accuracy and the least misclassification. **Logistic Regression** struggles with distinguishing between similar weight categories due to its linear nature. **Random Forest** improves classification performance significantly by capturing non-linear relationships, but still faces some misclassification issues in overlapping categories. **XGBoost** provides the most robust predictions, handling complex feature interactions effectively. Therefore, for obesity classification, XGBoost is the best-performing model in this study. Further improvements could be made by tuning hyperparameters or incorporating additional features.

## About Me
If you have any questions or would like to connect, feel free to reach out!

- **Email**: nafishusenromadani@gmail.com  
- **LinkedIn**: [nafishusen24](https://www.linkedin.com/in/nafishusen24/)  
- **Instagram**: [@nafishusen24](https://www.instagram.com/nafishusen24/)

