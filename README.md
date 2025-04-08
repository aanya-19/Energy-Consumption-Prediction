# 🔋 Energy Consumption Prediction
This project aims to predict building energy consumption based on various environmental and operational features such as temperature, humidity, occupancy, and equipment usage.

## 📁 Dataset
Source: Kaggle Dataset – Energy Consumption Prediction

Size: ~1000 rows

Format: CSV

## 📌 Features:
Column Name	Description
Timestamp	Date and time (parsed into year, month, day...)
Temperature	Indoor/Outdoor temperature
Humidity	Humidity percentage
SquareFootage	Area of the building
Occupancy	Number of people in the building
HVACUsage	On/Off status of HVAC system
LightingUsage	Energy used for lighting
RenewableEnergy	Energy contributed by renewables
DayOfWeek	Day name (converted to 0–6)
Holiday	Whether the day is a holiday
EnergyConsumption	🔥 Target variable: total energy consumed
🛠️ Tools & Libraries Used
Python

Pandas & NumPy for data preprocessing

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

