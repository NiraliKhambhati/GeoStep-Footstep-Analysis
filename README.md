# 📌 GeoStep: Footstep Analysis using Geophone Sensors

## 📌 Project Overview
GeoStep is an analytical project that explores footstep detection and activity recognition using geophone sensor data. The dataset contains various sensor readings, including energy, frequency, and statistical measures of vibrations caused by footsteps. This project applies data analysis and visualization techniques to extract meaningful patterns.

## 🌍 Why Geophone Sensors?
Geophones are vibration-sensitive devices used in seismology and structural monitoring. In this project, they help detect footstep patterns, making them valuable for applications in security surveillance, healthcare, and motion tracking. Understanding how energy and frequency components change with different activities provides insights into movement behavior.

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

## 📊 Results & Key Findings

- Energy levels are significantly higher in running compared to walking and jumping.
- Dominant frequency patterns show consistent peaks for certain activities, which can be used for classification.
- The heatmap analysis reveals a strong correlation between energy and dominant_freq, indicating a relationship between footstep force and frequency components.
- Temporal analysis suggests that footstep energy fluctuates depending on time intervals, useful for detecting patterns in movement behavior.

## 📊 Visualizations

🔥 Heatmap for feature correlations
📈 Energy trend plot over time
📊 Histograms for feature distributions
📦 Boxplot of energy levels by activity

## 📎 How to Use

🖥️ Clone the repository:
git clone https://github.com/NiraliKhambhati/GeoStep-Footstep-Analysis.git

📦 Install required libraries:
pip install pandas matplotlib seaborn numpy

📊 Run the Jupyter Notebook for analysis.

🛠 Dependencies
- Python 3.8+
- Pandas 1.3.5
- Matplotlib 3.4.3
- Seaborn 0.11.2

## 📌 Future Scope

🔹 Apply Machine Learning models to classify activities based on footstep signals.
🔹 Explore deep learning techniques for pattern recognition.
🔹 Develop a real-time footstep detection system.

## 👥 Contributors

- Nirali Khambhati - Project Lead & Data Analyst

- 📧 For Queries: Reach out via GitHub Issues or email!

## 🎯 Author: Nirali Khambhati
