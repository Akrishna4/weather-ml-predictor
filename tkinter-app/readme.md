
---

# 🌤️ Weather Prediction Application

A simple GUI-based weather prediction tool built with **Python** and **Tkinter**. It takes user input—such as date, precipitation, temperatures, and wind speed—and predicts the weather using a **Decision Tree Classifier** trained on historical data.

---

## 🛠️ How to Run

1. **Install Python**: [python.org/downloads](https://www.python.org/downloads/)
2. **Clone this repo** or download `main.py`, `calculation.py`, and `dataset.csv`.
3. **Install dependencies**:

   ```bash
   pip install pandas numpy scikit-learn
   ```
4. **Run the app**:

   ```bash
   python main.py
   ```

---

## ⚙️ How It Works

* User enters:

  * Date
  * Precipitation
  * Max/Min Temperature
  * Wind Speed
* Input is validated and processed.
* A dataset (`dataset.csv`) is loaded, cleaned (IQR filtering, skew transformation), and label-encoded.
* The **Decision Tree Classifier** is trained on this dataset.
* Input is transformed similarly, then passed to the trained model.
* **Predicted weather condition** is shown in the GUI.

---

## 📁 Project Structure

* `main.py` – GUI and event logic (Tkinter)
* `calculation.py` – Data preprocessing and ML prediction
* `dataset.csv` – Historical weather data

---

## 🚀 Features

* Easy-to-use Tkinter interface
* Real-time prediction with a trained ML model
* Data preprocessing: outlier removal, encoding, and scaling
* Simple, customizable ML pipeline

---

## 🧪 Future Improvements

* Add support for other ML models (e.g., Random Forest)
* Live weather API integration for dynamic predictions
* Save user input/predictions to a local file or DB

---

## 📌 About

A beginner-friendly project combining **GUI development** and **ML-based forecasting** to make weather prediction accessible and interactive.

---

