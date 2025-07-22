
---

# 🌦️ weather-ml-predictor

## 📌 Introduction

Weather prediction plays a vital role in numerous fields such as agriculture, transportation, and disaster management. While traditional forecasting models have improved over time, they often fall short in capturing complex, non-linear patterns. **Machine Learning (ML)** offers a promising alternative by learning from vast historical datasets and uncovering subtle trends in the data.

This project explores the application of **supervised ML algorithms** — including **Decision Trees**, **Logistic Regression**, and **K-Nearest Neighbors (KNN)** — to predict daily weather conditions. We utilize historical weather data from multiple weather stations within a specific region and build models to forecast future weather states.

### 🔍 Key Objectives:

* Evaluate various ML algorithms for weather prediction
* Analyze the impact of dataset size and feature quality on prediction accuracy
* Identify the most influential features for model performance

Through this project, we aim to highlight the capabilities and limitations of ML techniques in weather forecasting and promote further exploration of data-driven methods in climatology.

---

## ✅ Results

Among all models developed, the **Decision Tree model** using the `month` feature (extracted from the `date`) achieved the best performance with:

* **Max Depth:** 4
* **Accuracy:** **83.87%**

### 📊 Output Visualization:

![model\_output](https://github.com/Diwas524/Weather-Prediction-Using-Machine-Learning/blob/main/output.png)

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/weather-ml-predictor.git
   cd weather-ml-predictor
   ```

2. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or scripts to train models and evaluate accuracy.

---

## 📁 Dataset

The dataset includes daily weather measurements such as:

* Temperature
* Humidity
* Wind speed
* Pressure
* Date

These features are preprocessed and used to train classification models for weather prediction.

---

## 📚 Algorithms Used

* Decision Tree Classifier
* Logistic Regression
* K-Nearest Neighbors (KNN)

---

## 📈 Evaluation Metrics

* Accuracy
* Confusion Matrix

---

## 🧠 Future Improvements

* Incorporate time-series forecasting models (e.g., LSTM, ARIMA)
* Expand dataset across regions and years
* Add ensemble models like Random Forest and XGBoost

---

## 👨‍💻 Author

Project by [Akrishna4](https://github.com/Akrishna4) — updated and renamed to `weather-ml-predictor` for better clarity and presentation.

---

