# NDVI Land Cover Classification

## 📌 Project Overview
This project focuses on **classifying land cover types using NDVI (Normalized Difference Vegetation Index) time-series data**. 
We use Python and Logistic Regression to process noisy NDVI data and accurately predict land cover types for different regions.  

The main goal is to develop a **robust and reliable predictive model** for land cover classification using real-world NDVI signals.

---

## 🧰 Dataset
- **File:** hacktrain.csv  
- **Content:** NDVI time-series data for multiple land regions  
- **Features:** NDVI values over time, region identifiers, environmental indicators  
- **Target:** Land cover type (e.g., Forest, Water, Urban, Cropland)

---

## 🛠 Methodology
1. **Data Preprocessing**  
   - Handling missing NDVI values  
   - Normalization and scaling  
   - Preparing data for model input  

2. **Feature Engineering**  
   - Aggregating NDVI statistics (mean, max, min, trend)  
   - Encoding categorical variables  

3. **Modeling**  
   - Logistic Regression for multi-class classification  
   - Train-test split for evaluation  
   - Performance metrics: Accuracy, Confusion Matrix  

4. **Prediction**  
   - Predict land cover type for each region  
   - Structured output for analysis and visualization

---

## 📊 Results
- **Model Validation Accuracy:**  0.96 
- **Insights:** Model reliably classifies land cover types even with noisy NDVI data

---

## 🚀 How to Run
1. Clone the repository:  
   \\\bash
   git clone https://github.com/Vivankhat/ndvi_land_cover_classification.git
   \\\
2. Navigate to the project folder:  
   \\\bash
   cd NDVI_Project
   \\\
3. Install required packages:  
   \\\bash
   pip install -r requirements.txt
   \\\
4. Open the Jupyter notebook:  
   \\\bash
   jupyter notebook ndvi_land_cover_classification.ipynb
   \\\
5. Run all cells to preprocess data, train the model, and generate predictions

---

## 🖋 Author
**Vivan Khatri**  
- GitHub: [Vivankhat](https://github.com/Vivankhat)  
- Email: vivankhat20@gmail.com  

---

## 📝 License
**MIT License**  
Copyright (c) 2025 Vivan Khatri  
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the \
Software\), to deal in the Software without restriction, including the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software.


