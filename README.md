# 🌦️ Weather Prediction Model With Machine Learning
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/26066a4b-a476-46aa-8aa8-55be240267f6" />

📌 Project Overview: The Weather Prediction Model With Machine Learning project focuses on predicting weather-related parameters (such as temperature trends) using historical climate data and machine learning techniques.
The goal is to analyze past weather patterns and build a predictive model that can help understand future weather behavior.
This project demonstrates data preprocessing, feature engineering, model training, and evaluation using Python and popular ML libraries.

🎯 Objectives
1. Analyze historical weather and temperature data
2. Convert and preprocess raw text data into a structured format
3. Build a machine learning regression model for prediction
4.  Evaluate model performance using appropriate metrics

Key Features:
1. Date (Year extracted)
2. Land Average Temperature
3. Land Max Temperature
4. Land Min Temperature
5. Land and Ocean Average Temperature
6. Temperatures were converted from Celsius to Fahrenheit during preprocessing.

⚙️ Technologies Used
1. Programming Language: Python
2. Libraries & Tools:
3. NumPy
4. Pandas
5. Scikit-learn
6. Matplotlib / Seaborn (for visualization)
7. Jupyter Notebook

🧠 Machine Learning Model
1. Model Used: Random Forest Regressor
2. Why Random Forest?
A. Handles non-linear relationships well
B. Robust to noise
C. Works effectively with tabular data

🔄 Workflow
1. Data Collection: Load raw weather data from text files
2. Data Preprocessing: 
A. Clean column names
B. Handle missing values
C. Convert temperatures (°C → °F)
D. Extract Year from Date
3. Feature Engineering: Select relevant weather features
4. Model Training: Train Random Forest Regressor on training data
5. Model Evaluation: Metrics used:
A. R² Score
B. MAE (Mean Absolute Error)
C. RMSE (Root Mean Squared Error)
D. MAPE-based accuracy (for interpretability)

📊 Results
1. The model successfully learns historical weather patterns
2. Achieves reliable performance on validation data
3. Demonstrates the effectiveness of ensemble learning for weather prediction tasks.
