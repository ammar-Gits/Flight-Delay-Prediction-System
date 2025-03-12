# Flight Delay Prediction System

The **Flight Delay Prediction System** is a **machine learning-based** solution designed to analyze **historical flight and weather data** to predict **departure delays**. By leveraging advanced **classification and regression models**, the system helps airlines and passengers anticipate delays, improving operational efficiency and customer satisfaction.

## Features
- **Flight & Weather Data Integration** – Merges real-time weather conditions with flight schedules.
- **Binary Classification** – Predicts whether a flight will be on-time or delayed.
- **Multi-Class Classification** – Categorizes delays into No Delay, Short, Moderate, or Long.
- **Regression Analysis** – Predicts the exact delay duration in minutes.

## Development Process

### Phase 1: Data Preprocessing
- Handled missing values and standardized time formats.
- Engineered features like **Hour, Month, and Day of the Week**.

### Phase 2: Exploratory Data Analysis (EDA)
- Visualized **delay distributions** and identified key influencing factors.
- Examined weather impact on delays.

### Phase 3: Model Training
- Implemented **Random Forest Classifier** for binary and multi-class classification.
- Used **Random Forest Regressor** for delay duration prediction.

### Phase 4: Model Optimization & Validation
- Tuned hyperparameters using **GridSearchCV**.
- Applied **cross-validation** to ensure model reliability.

### Phase 5: Model Testing & Submission
- Generated predictions in the required format for **Kaggle competition** evaluation.

## Technologies Used
- **Python** (Data Processing & Model Development)
- **Pandas & NumPy** (Data Preprocessing)
- **Scikit-Learn** (Machine Learning Models)
- **Matplotlib & Seaborn** (Data Visualization)

## Results
- **Binary Classification Accuracy:** 85%+
- **Multi-Class Classification Accuracy:** 78%+
- **Regression (Mean Absolute Error):** ~15 minutes
