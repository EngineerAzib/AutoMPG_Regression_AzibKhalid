# Auto MPG Prediction: Regression Methods Comparison  
**CS 229 – Machine Learning Project**  
**Student**: Azib Khalid  
**Date**: November 02, 2025  

---

## Open in Google Colab (Click Below)

https://colab.research.google.com/drive/1wnnP9aHmJkAxGyN5l7RIius675ez5g0v#scrollTo=bCy-QeweBWyN

> **After opening, save a copy to your Drive → Run all cells**

---

## Project Overview

Predict **MPG** using **7 regression methods** on the **UCI Auto MPG dataset**.

| Method | Test MSE |
|-------|----------|
| **Ridge** | **8.15** |
| **MLP**   | **8.10** (Best) |
| OLS/SVD/GD | 8.20 |
| PCA (k=4) | 8.45 |

---

## Dataset (Auto-downloaded in Colab)

```python
url = "https://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data"
