# AgriStorm Sentinel — Weather Anomaly Detection (Model 1)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00BFFF&center=true&vCenter=true&width=850&lines=AgriStorm+Sentinel;AI-Powered+Weather+Anomaly+Detection;Monitoring+Weather+Patterns+Across+Rajasthan;Powered+by+Machine+Learning" alt="AgriStorm Animated Banner" />
</p>

<p align="center">
  <strong>Intelligent Weather Monitoring | Anomaly Detection | Rajasthan, India</strong>
</p>

---

An ML-based weather anomaly detection system designed for Rajasthan, India. It analyzes historical ERA5 weather data (2000–2025) across seven cities to identify unusual weather patterns.

## Models Used

- Global Isolation Forest
- City-Specific Isolation Forest
- Autoencoder-style MLP
- Statistical MAD Detection
- Hybrid Voting Ensemble

## Features

- Detects unusual temperature, rainfall, humidity, pressure, and wind patterns.
- Supports city-specific anomaly detection.
- Uses historical weather patterns for anomaly identification.
- Combines multiple detection approaches through a hybrid ensemble.

## Dataset

- **Source:** ERA5 Reanalysis via Open-Meteo Historical Weather API
- **Period:** 2000–2025
- **Locations:** Jaipur, Jodhpur, Kota, Baran, Bikaner, Jaisalmer, Udaipur
- **Records:** 66,479 daily observations

## Tech Stack

Python | Scikit-learn | Pandas | NumPy | Google Colab

## Project Structure

```text
Model_1_V2/
├── agristorm_model1_v2.pkl
├── all_model_predictions.csv
├── model_comparison.csv
├── city_wise_report.csv
├── top_anomalies.csv
└── validation/
```

## Important Note

This model identifies statistically unusual weather patterns. It does not independently forecast or confirm extreme weather disasters.

## Part of AgriStorm Sentinel

Model 1 is the first intelligence layer of AgriStorm Sentinel, an agricultural weather-risk monitoring and early-warning system.

---

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=00CFFF&center=true&vCenter=true&width=600&lines=Building+Smarter+Weather+Intelligence;Data+Driven.+AI+Powered.+Agriculture+Focused." alt="Animated Footer" />
</p>

<p align="center">
  <strong>AgriStorm Sentinel | Model 1</strong>
</p>
