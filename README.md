# Crop and Fertilizer Recommendation System

This repository provides a dataset designed for developing a **Crop and Fertilizer Recommendation System**. The dataset integrates crucial information about soil characteristics, environmental conditions, and fertilizers, enabling the creation of intelligent systems to recommend both optimal crops and the appropriate fertilizers. The goal is to enhance agricultural productivity and sustainability by leveraging data-driven insights.

---

## Dataset Overview

The dataset is structured to provide a comprehensive resource for building recommendation systems in agriculture. It includes data points essential for predicting suitable crops and fertilizers based on soil, climate, and nutrient conditions.

### Features
1. **Soil Information**:
   - Nitrogen (N), Phosphorus (P), Potassium (K) levels
   - pH levels and other soil properties

2. **Climate Data**:
   - Temperature (°C), Humidity (%), Rainfall (mm)

3. **Crop Labels**:
   - Categorical labels for crops (e.g., Wheat, Rice, Maize, etc.)

4. **Fertilizer Data**:
   - Recommendations for fertilizers based on soil type and nutrient deficiencies
   - Includes details for common fertilizers such as Urea, DAP, MOP, and Organic Manure
   - Provides insights into the type and quantity of fertilizer needed to improve soil health and crop yield

---

## Applications

This dataset can be used in a variety of agricultural and environmental research areas:
- **Crop Recommendation**: Identify the most suitable crops based on soil and environmental conditions.
- **Fertilizer Recommendation**: Suggest optimal fertilizers to address nutrient deficiencies in the soil.
- **Precision Agriculture**: Develop data-driven tools for improving farming practices and increasing productivity.
- **Agricultural Advisory Systems**: Build comprehensive systems for farmers to receive recommendations on both crops and fertilizers.

---

## Sample Dataset Insights

- **Crop Recommendation**:
  - Based on the combination of soil properties (N, P, K levels), climate conditions, and rainfall patterns, the dataset helps predict the best crop to cultivate in a given region.

- **Fertilizer Recommendation**:
  - Analyzes nutrient deficiencies in the soil and suggests fertilizers to restore balance.  
  - For instance:
    - High nitrogen deficiency → Suggest Urea
    - Low phosphorus levels → Recommend DAP
    - Potassium imbalance → Use MOP (Muriate of Potash)
    - Organic matter improvement → Suggest Organic Manure

---

## Format

The dataset is stored in `.csv` format and includes the following columns:
- `Nitrogen (N)`  
- `Phosphorus (P)`  
- `Potassium (K)`  
- `pH`  
- `Temperature (°C)`  
- `Humidity (%)`  
- `Rainfall (mm)`  
- `Crop Label`  
- `Fertilizer Type`  
- `Fertilizer Quantity (kg/ha)`

---
