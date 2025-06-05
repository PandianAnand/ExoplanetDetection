# Searching for Exoplanets with Machine Learning 🚀🔭

This project explores how machine learning can be used to identify exoplanets using NASA's Kepler dataset. It was developed as part of the Inspirit AI Scholars program.

## 📊 Project Overview
Using classification models like logistic regression and random forests, this project analyzes light curves to predict the presence of exoplanets.

## 🧠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-Learn
- Machine Learning
- Matplotlib & Seaborn

## 📁 Files
- `exoplanet-search.ipynb`: Main Jupyter notebook with all analysis and results.

## 🔍 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook in Jupyter

## 📌 Results
- Achieved **94.92% accuracy** using a Random Forest Classifier on the NASA Kepler exoplanet dataset.
- Key insight: The most important features for the model were `koi_fpflag_co`, `koi_prad`, and `koi_period`, suggesting that false positive indicators, planetary radius, and orbital period are critical in determining whether a candidate is a real exoplanet.

## 👤 Author
Pandian Anand – https://www.linkedin.com/in/pandian-anand-4bb1b1218/

