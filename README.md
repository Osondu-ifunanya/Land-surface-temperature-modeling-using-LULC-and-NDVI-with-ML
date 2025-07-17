
## 🌍 Land Surface Temperature Modeling using LULC and NDVI

This project models **Land Surface Temperature (LST)** using synthetic data that simulates remote sensing variables like **NDVI**, **Land Use Land Cover (LULC)**, and **Elevation**. A **Random Forest regression** model is used to predict LST values, helping explore the relationship between land surface conditions and temperature variation.

---

### 📁 Project Structure

* `lst_modeling_results.xlsx` – Output predictions of LST vs actual values.
* `main.py` – Python script that generates synthetic data, trains the ML model, and evaluates predictions.

---

### 📊 Features Used

* **NDVI** – Normalized Difference Vegetation Index
* **LULC** – Simulated land cover types (Urban, Forest, Water, etc.)
* **Elevation** – Terrain height in meters

---

### 🚀 Model

* **Algorithm**: Random Forest Regression
* **Evaluation**: RMSE and R² score
* **Purpose**: Simulate LST dynamics for climate/environmental applications

---

### 🧪 How to Run

```bash
pip install pandas numpy scikit-learn openpyxl
python main.py
```

---

### 📌 Author

**Ifunanya Blessing**
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com) | Climate & GeoAI Researcher


