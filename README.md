The Simulated Crop Yield Prediction Dataset is designed to support machine learning and predictive analytics projects focused on agriculture. This dataset contains 1,000 samples of simulated agricultural data, representing key environmental and input factors that influence crop productivity. It is ideal for testing regression models and other predictive algorithms aimed at estimating crop yields based on specific conditions.

The dataset includes seven essential features: Temperature (°C), which indicates the average temperature during the crop’s growing season; Rainfall (mm), representing the total rainfall received; Soil pH, measuring the acidity or alkalinity of the soil; and Soil Moisture (%), capturing the moisture content of the soil. Additionally, Fertilizer Used (kg/ha) records the amount of fertilizer applied per hectare, and Crop Type categorizes each entry by crop, with options including Rice, Wheat, and Maize. The Yield (tonnes/ha) variable represents the target variable for prediction, showing the productivity of each crop in tonnes per hectare.

This dataset is provided in CSV format, named simulated_crop_yield_dataset.csv, and contains 1,000 entries with the features mentioned above. It is particularly useful for educational and research purposes, offering a controlled environment for developing and testing various machine learning models. The dataset is especially suitable for predictive modeling in agriculture, enabling researchers to explore techniques such as linear regression, decision trees, neural networks, and ensemble methods. Additionally, it can be used to practice model interpretability techniques, like SHAP, to analyze feature importance.

Libraries Used
The following Python libraries were used to create, preprocess, and analyze this dataset:

NumPy: For numerical operations, random data generation, and array handling.
Pandas: For data manipulation, organization, and CSV handling.
Scikit-Learn: For data preprocessing (e.g., StandardScaler, LabelEncoder), machine learning models (e.g., RandomForestRegressor), and model evaluation metrics.
TensorFlow/Keras: To build and train neural network models for yield prediction.
Keras Tuner: For hyperparameter tuning of the neural network.
SHAP: For interpretability, to analyze feature importance and understand the impact of each feature on predictions.
Matplotlib: For data visualization, including plots of actual vs. predicted yields and SHAP summary plots.
