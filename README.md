# Weighted Clusterwise Linear Regression (WCLR)
### Using Adaptive Quadratic Form Distance

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/language-Python-blue.svg)
![Status](https://img.shields.io/badge/status-Active-green)

## 📌 Project Overview
Weighted Clusterwise Linear Regression (WCLR) is a hybrid approach that combines **clustering and regression** by introducing adaptive weight matrices and quadratic distance measures. This method enhances accuracy and interpretability in **heterogeneous datasets** by effectively partitioning data into meaningful clusters and assigning **specific regression models** to each.

### 🔥 Key Features
- **Clusterwise Regression (CR):** Partition large datasets into homogeneous clusters, each modeled by a separate linear regression.
- **Adaptive Quadratic Distance:** Uses positive definite matrices to improve clustering accuracy.
- **Weight Optimization:** Incorporates different constraint-based weighting schemes to enhance performance.
- **Application Areas:** 
  - Housing Price Prediction 🏡
  - Customer Segmentation 📊
  - Financial Forecasting 💰
  - Anomaly Detection 🚨

---

## 📁 Repository Structure

```bash
📦 WCLR_Project
├── 📄 README.md         # Project documentation
├── 📄 LICENSE           # License details (MIT)
├── 📄 requirements.txt  # Required dependencies
├── 📂 src               # Source code implementation
│   ├── data_processing.py
│   ├── clustering.py
│   ├── regression.py
│   ├── main.py
│   ├── utils.py
│   ├── visualization.py
├── 📂 notebooks         # Jupyter notebooks for testing
│   ├── WCLR_Analysis.ipynb
├── 📂 reports           # Project reports
│   ├── WCLR_REPORT.pdf  # Detailed project report
│   ├── WCLR_PRESENTATION.pdf  # Presentation slides
├── 📂 datasets          # Sample datasets used
│   ├── housing_data.csv
│   ├── customer_data.csv
└── 📂 tests             # Unit tests for model verification
    ├── test_clustering.py
    ├── test_regression.py
