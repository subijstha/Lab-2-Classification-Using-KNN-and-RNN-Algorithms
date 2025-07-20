# MSCS_634_Lab_2: KNN vs RNN Classification - Wine Dataset

## 📌 Purpose
This lab investigates the performance of two popular classification algorithms: **K-Nearest Neighbors (KNN)** and **Radius Neighbors (RNN)** using the **Wine Dataset** from scikit-learn. The objective is to understand how varying `k` and `radius` parameters influence model accuracy and to develop insights on classifier performance.

## ✅ Summary of Results
- **KNN** performed consistently well, peaking with **k = X**.
- **RNN** showed more variation, achieving highest accuracy with **radius = Y**.
- KNN was generally more stable on this dataset.

## 📊 Accuracy Trends
- **KNN**: Accuracy increases initially with k but may plateau or slightly drop at higher k.
- **RNN**: Performance varies based on radius, with too large a radius leading to instability.

## 💡 Key Takeaways
- KNN is preferable for small datasets and when you have a clear sense of neighborhood.
- RNN may be useful in cases with well-separated clusters, but requires careful tuning.

## ⚠️ Challenges Faced
- Setting appropriate `radius` values was tricky due to scale sensitivity.
- Outliers and imbalanced data slightly affected the RNN model.

---

## 📂 Contents
- `Lab2_KNN_RNN_Wine.ipynb` – Full code with results and visualizations.
- `README.md` – Overview and findings.

