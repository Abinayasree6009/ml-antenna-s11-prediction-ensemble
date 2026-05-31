# Rapid Return Loss Prediction for Microstrip Patch Antennas using Ensemble ML

## Overview
Compared 5 ensemble machine learning models to predict antenna S11 return 
loss instantly — replacing slow CST Studio simulations.

## Results
| Model | R² Score | MAE |
|-------|----------|-----|
| **XGBoost** | **0.9887** | **0.083 dB** | **THE BEST**
| CatBoost | 0.9867 | 0.135 dB |
| Extra Trees | 0.9825 | 0.110 dB |
| LightGBM | 0.9807 | 0.156 dB |
| Random Forest | 0.9674 | 0.148 dB |

⚡ Speed: 900,000× faster than CST software's traditional simulation!

## Dataset
- Source: Kaggle (publicly available dataset)
- Records: 11,011 antenna configurations  
- Input: Patch length, Patch width, Frequency
- Output: S11 return loss (dB)
- Link: https://www.kaggle.com/code/mshabrawy/rectangular-patch-antenna/input

## Tools Used
- Python, Scikit-learn, XGBoost, LightGBM, CatBoost
- Google Colab

## GUI
Built an interactive GUI where users input antenna dimensions 
and get instant S11 prediction — no simulation needed!

## Author
R.J. Abinaya Sree — M.E. Communication Systems,
Government college of engineering, Tirunelveli
