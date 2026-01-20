# Multivariate Time-Series Anomaly Detection for Equipment Sensors

## 📌 Project Overview
This project focuses on detecting anomalies in multivariate time-series data
collected from equipment sensors. The objective is to identify abnormal sensor
behavior that may indicate equipment faults, unexpected operating conditions,
or the need for maintenance.

The project demonstrates a complete data science workflow including exploratory
data analysis, preprocessing, anomaly detection, visualization, and result
interpretation.

---

## 🧠 Techniques Used
- Exploratory Data Analysis (EDA)
- Statistical analysis of sensor data
- Data preprocessing and feature scaling
- Isolation Forest (unsupervised anomaly detection)
- LSTM Autoencoder (documented approach for sequence-based detection)
- Anomaly visualization and validation strategies

---

## 🛠 Technologies & Tools
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

> Note:  
> LSTM Autoencoder and tsfresh-based feature extraction are documented in the
> notebook. Their execution requires a local environment with additional
> dependencies.

---

## 📂 Project Structure
Multivariate-TimeSeries-Anomaly-Detection/
│
├── data/
│ └── equipment_sensors.csv
│
├── notebooks/
│ └── Multivariate_TimeSeries_Anomaly_Detection.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore


---

## 📊 Dataset Description
The dataset contains multivariate time-series sensor readings collected at
regular time intervals. Each row represents multiple sensor values recorded
at a specific timestamp.

Since the original dataset was not provided, a realistic synthetic dataset
was generated to demonstrate the complete anomaly detection pipeline.

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to:
- Understand sensor trends over time
- Analyze statistical properties of sensor readings
- Study distributions and correlations between sensors
- Identify potential abnormal patterns visually

These steps help ensure that the data is well understood before applying
anomaly detection models.

---

## 🚀 Anomaly Detection Approach

### Isolation Forest
Isolation Forest is used as the primary anomaly detection model due to its
effectiveness in unsupervised settings and high-dimensional data. It isolates
outliers by randomly partitioning the feature space.

Detected anomalies are visualized on sensor time-series plots to validate
model behavior.

### LSTM Autoencoder (Documented)
The LSTM Autoencoder approach is documented as a sequence-based method that
learns normal temporal patterns and detects anomalies using reconstruction
error. This method is well-suited for capturing temporal dependencies and
gradual sensor drifts.


## 📈 Results
- Isolation Forest successfully identified anomalous sensor readings
- Multiple visualizations support anomaly detection results
- Statistical and distribution-based validation confirms model behavior
- The combined approach provides a robust framework for sensor monitoring

## 🔮 Future Improvements
- Full LSTM Autoencoder implementation in a local environment
- Real-time anomaly detection pipeline
- Integration with monitoring dashboards
- Deployment as a predictive maintenance system

## ▶️ How to Run the Project

1. Clone the repository:

git clone https://github.com/Shreya2345shrivastava/Multivariate-TimeSeries-Anomaly-Detection.git

Navigate to the project folder:

cd Multivariate-TimeSeries-Anomaly-Detection


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook notebooks/Multivariate_TimeSeries_Anomaly_Detection.ipynb

👩‍💻 Author

Shreya Shrivastava
B.Tech CSE | Data Science & Analytics