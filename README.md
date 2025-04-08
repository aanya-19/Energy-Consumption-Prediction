# 🔋 Energy Consumption Prediction
This project aims to predict building energy consumption based on various environmental and operational features such as temperature, humidity, occupancy, and equipment usage.

## 📁 Dataset
Source: Kaggle Dataset – Energy Consumption Prediction

Size: ~1000 rows

Format: CSV

## 📌 Features:
| Feature           | Description                                      |
|-------------------|--------------------------------------------------|
| `Timestamp`        | Date and time (later split into year, month, etc.) |
| `Temperature`      | Indoor/Outdoor temperature                       |
| `Humidity`         | Relative humidity                                |
| `SquareFootage`    | Building area in square feet                     |
| `Occupancy`        | Number of people in the building                 |
| `HVACUsage`        | HVAC status (encoded: 0 = Off, 1 = On)          |
| `LightingUsage`    | Energy used for lighting (numeric)              |
| `RenewableEnergy`  | Energy supplied by renewable sources             |
| `DayOfWeek`        | Day (encoded: 0 = Monday, ..., 6 = Sunday)      |
| `Holiday`          | Holiday flag (`Yes`/`No`)                        |
| `EnergyConsumption`| ✅ **Target variable**                           |


## 🛠️ Tools & Libraries Used
Python

Pandas for data preprocessing

Seaborn & Matplotlib for visualization

Scikit-learn for model building & evaluation

## 📊 Exploratory Data Analysis (EDA)
🔹 KDE Plots to visualize the distribution of energy consumption

🔹 Correlation heatmaps to identify important features

🔹 Grouped visualizations by DayOfWeek, Occupancy, SquareFootage to observe patterns

## 🧠 Model Training
Input: 9 features (excluding Timestamp)

Target: EnergyConsumption

Model(s) tried:

Linear Regression (R² ≈ 63%)


## 🔍 Key Insights
Energy consumption is highly influenced by:

HVAC usage

Occupancy

Square footage

