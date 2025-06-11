# Searching for Exoplanets with Machine Learning 🚀🔭

This project explores how machine learning can be used to identify exoplanets using NASA's Kepler dataset. It was developed as part of the Inspirit AI Scholars program.

## 📊 Project Overview
Using classification models like logistic regression and random forests, this project analyzes light curves to predict the presence of exoplanets.

## 🚀 Project Workflow

The project is divided into three google colab notebooks, each representing a key stage of the machine learning pipeline:

1. **Section 1** – Data exploration and preprocessing
2. **Section 2** – Feature engineering and model training
3. **Section 3** – Model evaluation and results interpretation

## 🧠 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-Learn
- Machine Learning
- Matplotlib & Seaborn

## 📁 Files
- `Student_PlanetHunters_Section1.ipynb`: 📊 Initial data exploration and preprocessing of Kepler exoplanet candidate data.
- `Student_PlanetHunters_Section2.ipynb`: ⚙️ Feature engineering and training a Random Forest Classifier.
- `Student_PlanetHunters_Section3.ipynb`: 📈 Evaluation of model performance and analysis of feature importance.

## 🔍 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook in google colab

## 📌 Results
- Achieved **99.12% accuracy** using a Random Forest Classifier on the NASA Kepler exoplanet dataset.
- Key insight: The most important features for the model were `koi_fpflag_co`, `koi_prad`, and `koi_period`, suggesting that false positive indicators, planetary radius, and orbital period are critical in determining whether a candidate is a real exoplanet.

## 👤 Author
Pandian Anand – https://www.linkedin.com/in/pandian-anand-4bb1b1218/

