# IoT-Based Cardiovascular Monitoring System for Diabetic Patients

## Overview
An intelligent IoT solution that provides continuous cardiovascular monitoring for diabetic patients through non-invasive sensors. The system combines hardware sensors, real-time data processing, and machine learning analytics to detect anomalies and track vital sign trends.

## Key Features
- Multi-sensor integration (ECG, Temperature, Heart Rate, SpO2)
- Real-time vital signs monitoring and visualisation
- Machine Learning-powered analysis:
  - Anomaly detection using Isolation Forest
  - Trend analysis with Exponential Smoothing
  - Health state classification using Random Forest
- Secure data storage with MongoDB
- Interactive web dashboard built with Streamlit

## Technical Architecture
- Dual-controller system (Arduino + Raspberry Pi)
- Python-based data processing and analysis
- Web-based visualisation and monitoring interface
- Secure data transmission and storage

## Technologies Used
- Hardware: Arduino, Raspberry Pi, MAX30102, ECG sensors
- Backend: Python, MongoDB
- Frontend: Streamlit
- ML Libraries: scikit-learn, numpy, pandas
