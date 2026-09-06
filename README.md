# Seasonal Agriculture Performance Analysis

## Overview
Agricultural activities are heavily influenced by seasonal variations, environmental conditions, farming practices, and resource availability. This repository provides an end-to-end data processing and analytics workflow conducted on a 4,000-record agricultural dataset spanning **Kharif**, **Rabi**, and **Zaid** cropping seasons.

The project evaluates climate strain, resource consumption, and regional crop profitability to provide actionable insights for farmers, agribusinesses, and agricultural extension officers.

---

## Key Features & Findings

* **Data Processing & Imputation**: Addressed missing values across environmental and yield metrics (`Rainfall_mm`, `Soil_Moisture_pct`, `Yield_Tonnes_Ha`) using KNN Imputation (`k=5`).
* **Univariate & Bivariate Distribution**: Analyzed farm counts across seasons and identified that **Kharif** generates the highest average net profit, whereas **Zaid** exhibits lower or net-negative average profitability due to elevated summer operational and irrigation costs.
* **Irrigation Efficiency & Economics**: Evaluated farm performance across irrigation methods (Drip, Flood, Rainfed, Sprinkler). Modern micro-irrigation systems (**Drip Irrigation**) deliver significantly higher profit margins compared to traditional flood irrigation.
* **Regional Crop Profitability Matrix**: Mapped average net profitability across Indian states and crop types. High-value cash crops such as **Chilli** and **Sugarcane** yield high net returns in key state corridors, while staple crops (Rice, Wheat) maintain yield stability during their optimal growing seasons.

---

## Repository Structure

```text
├── Major Project_Seasonal Agriculture Performance Analysis.pdf
├── PallaviR_SeasonalAgriculturePerformance.ipynb
├── PallaviR_VOIS_Major_Project_PPT_Submission.pptx
├── README.md
└── seasonal_agriculture_performance_analysis.csv                                 
