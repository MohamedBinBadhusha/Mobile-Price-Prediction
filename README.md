# Mobile-Price-Prediction

This project focuses on building a machine learning model to classify mobile phones into different price ranges based on their specifications and features. The goal is to predict whether a mobile phone falls into one of four price categories: low, medium, high, or very high cost.

Dataset Overview

The dataset contains various features of mobile phones, such as:

    Battery Power
    RAM
    Internal Memory
    Primary & Front Camera megapixels
    Screen Dimensions & Resolution
    Processor Specs (Clock Speed, Number of Cores)
    Connectivity Features (3G, 4G, Bluetooth, WiFi, Dual SIM)
    And more...

The target variable is price_range with four classes:

    0: Low Cost
    1: Medium Cost
    2: High Cost
    3: Very High Cost

Objective

    Classify mobile phones into the correct price range based on specifications.
    Analyze feature importance and relationships with price.
    Compare different classification algorithms to find the best-performing model.

Methods & Models Used

    Data Preprocessing: Checked for missing values, duplicates, and outliers.
    Feature Engineering: Created new features like screen_area, px_density, and memory_per_core.
    Exploratory Data Analysis (EDA): Visualized distributions and correlations.
    Models Applied:
        Logistic Regression (best performer: ~96.5% accuracy)
        Random Forest Classifier (~89% accuracy)
    Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.

Results

Logistic Regression achieved the best performance, indicating linear relationships in the dataset. Random Forest performed decently but was slightly less accurate.
