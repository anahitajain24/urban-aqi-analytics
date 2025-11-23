# 🏙️ Urban AQI Forecasting & Policy Simulation

### 📊 Machine Learning for Environmental Analytics

A comprehensive data pipeline that analyzes Delhi's air quality data to predict AQI (Air Quality Index) and simulate the impact of environmental policies.

## 🚀 Key Features
* **Multi-Model Evaluation:** Benchmarked Linear Regression, Random Forest, and Gradient Boosting.
* **Explainable AI:** visualized Feature Importance to identify PM2.5 and PM10 as the primary drivers of AQI.
* **Policy Simulator:** Includes a "What-If" engine to calculate the net AQI improvement resulting from hypothetical reductions in specific pollutants.

## 📈 Results
* **Best Model:** Random Forest Regressor
* **Key Finding:** A 20% reduction in PM2.5 levels results in a measurable ~X point drop in AQI (based on test samples).

## 🛠 Tech Stack
* **Language:** Python
* **ML:** Scikit-Learn (Cross-Validation, StandardScaler)
* **Data:** Hugging Face Datasets, Pandas
* **Viz:** Seaborn, Matplotlib

## 💻 How to Run
```bash
pip install -r requirements.txt
python main.py
