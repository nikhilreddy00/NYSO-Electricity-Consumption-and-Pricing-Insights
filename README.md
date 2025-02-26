# NYISO Electricity Consumption and Pricing Insights

## 📌 Project Overview

This project dives into analyzing electricity consumption and pricing data from the New York Independent System Operator (NYISO). The dataset encompasses detailed time-series data on electricity prices, load demand, and power grid operations. The primary aim is to harness big data techniques for forecasting electricity prices, detecting anomalies, and predicting future electricity demand.

## 📊 Dataset Information

The project utilizes data spanning from 2001 to 2023, concentrating on three pivotal datasets:

- **Pricing Data**: Locational-Based Marginal Prices (LBMP) reflecting real-time and day-ahead electricity costs.
- **Power Grid Data**: Transmission constraints, generation mix, and system stability indicators.
- **Load Data**: Real-time and forecasted electricity demand across NYISO regions.

**Dataset Source**: [NYISO Website](https://www.nyiso.com/)

## ⚙️ Project Objectives

The key objectives of this project include:

- **Predict electricity prices (LBMP)** based on historical load demand patterns.
- **Detect price anomalies** due to sudden grid condition changes (e.g., congestion or transmission losses).
- **Forecast future electricity demand** based on historical pricing and grid conditions.

Data from March, June, September, and December is utilized for prediction, while the remaining months serve as training data.

## 🛠 Tools & Technologies Used

- **Big Data Processing**: PySpark, Structured Streaming
- **Machine Learning Models**: MLlib, scikit-learn
- **Data Visualization**: Matplotlib, Seaborn
- **Data Handling**: Pandas, NumPy

## 📈 Results & Insights

- **Price Prediction**: Achieved high accuracy in forecasting LBMP using historical data.
- **Anomaly Detection**: Successfully detected price spikes due to congestion and system instability.
- **Demand Forecasting**: Accurately predicted future electricity load patterns, aiding in grid management.

**Notebook Environment**: Google Colab

## 📌 Future Work

- **Enhance model performance** using hyperparameter tuning and deep learning models.
- **Integrate real-time streaming data** from NYISO for live analysis.
- **Explore additional datasets** for a more comprehensive energy market analysis.

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the project, feel free to fork the repository and submit a pull request.

## 📬 Contact

For any questions or suggestions, reach out via GitHub issues or email.
