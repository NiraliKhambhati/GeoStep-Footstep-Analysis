# GeoStep-Footstep-Analysis

## 📌 Project Overview
GeoStep is an analytical project that explores footstep detection and activity recognition using geophone sensor data. The dataset contains various sensor readings, including energy, frequency, and statistical measures of vibrations caused by footsteps. This project applies data analysis and visualization techniques to extract meaningful patterns.

## 📂 Dataset Description
The dataset (geophone-sensor-data.csv) consists of 1800 rows with the following columns:

- timestamp → Time of data capture
- mean, std_dev, min, max, median → Statistical measures of vibration intensity
- dominant_freq → Frequency component of the detected vibration
- energy → Total energy of the detected signal
- activity → Activity type (e.g., walking, running, jumping)
- name → Identifier of the individual generating the footsteps

## 🚀 Analysis & Insights

1️⃣ Data Preprocessing

✅ Checked for missing values and confirmed dataset integrity.
✅ Identified numeric vs. non-numeric columns for analysis.

2️⃣ Statistical Analysis

✅ Generated a correlation matrix to identify relationships between features. 
✅ Visualized correlations using a heatmap.

3️⃣ Feature Distribution Analysis

✅ Histograms show how key features (mean, std_dev, energy) are distributed. 
✅ Helps in understanding variations in footstep intensity.

4️⃣ Activity-Wise Comparison

✅ Computed mean values of energy & vibration features for different activities. 
✅ Boxplot visualization to compare energy distribution across activities.

5️⃣ Time-Series Trend Analysis

✅ Converted timestamps to datetime format.
✅ Resampled data to analyze energy trends over time.
✅ Trend plot reveals fluctuations in footstep energy at different times.

## 📊 Visualizations

🔥 Heatmap for feature correlations

📈 Energy trend plot over time

## 📊 Histograms for feature distributions

📦 Boxplot of energy levels by activity

📎 How to Use

## Clone the repository:

git clone https://github.com/NiraliKhambhati/GeoStep-Footstep-Analysis.git

## Install required libraries:

pip install pandas matplotlib seaborn numpy

Run the Jupyter Notebook for analysis.

## 📌 Future Scope

🔹 Apply Machine Learning models to classify activities based on footstep signals.

🔹 Explore deep learning techniques for pattern recognition.

🔹 Develop a real-time footstep detection system.

