# EntriElevate-final-capstoneproject
Project_Final_capstone_entrielevate_BRFSS_nutrition_physicalactivity_obesity_data_analysis_submission repo

Final Capstone Project EntriElevate

This project focuses on analyzing and predicting public health metrics such as obesity rates, nutrition indicators, and physical activity levels using a cleaned dataset of 33 features and over 10,000 records. The goal is to build a reliable machine learning model that accurately estimates the Data_Value—a key health measurement—based on demographic, geographical, and categorical variables. Raw dataset liks: The dataset is collected from link: https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system (link from DATA.GOVT) Googledrive link: https://drive.google.com/file/d/1ndiEhnUz800iv3LWfrBrfto7xjVMVzPL/view?usp=sharing

Steps Done in the Project

Dataset Overview Analyzed a dataset with 33 columns and 10,676 rows containing health-related indicators.

1.Data Cleaning
Removed missing and irrelevant records Treated outliers using IQR method Converted necessary columns to appropriate data types

2.Feature Selection & Preprocessing
Selected 10+ key features based on data relevance Applied Label Encoding for most relevant categorical variables Separated features (X) and target (y = Data_Value)

3.Exploratory Data Analysis (EDA)
Visualized trends based on location, gender, race, topic, and year Identified patterns and data distribution using bar charts, boxplots, and heatmaps

4.Model Building
Built regression models: Linear Regression, Decision Tree, Random Forest, Gradient Boosting Trained models using the processed dataset

5.Model Evaluation Evaluated model performance using R² Score and Root Mean Squared Error (RMSE) Identified Random Forest as the best-performing model with highest R² and lowest RMSE

Conclusion & Insights
Key variables like topic, gender, location, and race significantly impact health outcomes Random Forest model can be effectively used for predictive public health analytics
