# 🌍 Clustering Global Development

## 📌 Business Objective

This project focuses on analyzing **world development indicators** using clustering techniques. By grouping countries based on socio-economic and development measures, the study identifies natural clusters that reveal **global development trends and disparities**.

---

## 🎯 Project Objectives

1. **Data Collection & Preprocessing** – Gather, clean, and preprocess global development datasets.
2. **Clustering Analysis** – Apply **K-Means, Hierarchical (Agglomerative), and DBSCAN** clustering.
3. **Insights Generation** – Identify patterns and compare developed vs. developing regions.
4. **Visualization** – Use charts and maps to represent clustering results.
5. **Final Deliverables** – Working clustering model, interactive dashboard, and presentation.

---

## 📊 Dataset Details

* **Name:** `World_development_mesurement.csv`
* **Rows:** 2976
* **Columns:** 25 (19 numerical, 6 categorical)
* **Key Features Include:**

  * `Birth Rate` – Proportion of live births
  * `Business Tax Rate` – Tax burden on businesses
  * `CO2 Emissions` – National CO₂ emissions
  * `Ease of Business` – Global ranking of ease of doing business
  * `GDP` – Gross Domestic Product (USD)
  * `Health Exp % GDP` – Healthcare expenditure as % of GDP
  * `Infant Mortality Rate` – Proportion of infant deaths
  * `Life Expectancy Male/Female` – Average life expectancy
  * `Population 0–14, 15–64, 65+` – Demographic splits
  * `Tourism Inbound/Outbound` – Tourism revenues and spending

---

## 🏗️ Project Structure

```
📁 Agglomerative-Clustering
 ┣ 📜 app.py                                    # Streamlit Application
 ┣ 📜 agglo_model.pkl                           # Saved Agglomerative Model
 ┣ 📜 scalerrs.pkl                              # Scaler used in preprocessing
 ┣ 📜 World_development_mesurement.csv          # Input Data
 ┣ 📜 requirements.txt                          # Dependencies
 ┣ 📜 README.md                                 # Project Documentation
 ┣ 📜 Group_4_P-575_Clustering-Gloabal_Development.ipynb  # Jupyter Notebook
```

---

## ⚙️ Usage

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Agglomerative-Clustering.git
cd Agglomerative-Clustering
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook (for exploration)

```bash
jupyter notebook Group_4_P-575_Clustering-Gloabal_Development.ipynb
```

### 4️⃣ Launch the Streamlit app

```bash
streamlit run app.py
```

### 5️⃣ Workflow inside Streamlit

* 📤 Upload `World_development_mesurement.csv`
* ⚙️ Data is **cleaned and scaled**
* 📊 Countries are clustered using **Agglomerative Clustering**
* 🌍 Interactive visualizations display global development clusters

---

## 🧰 Tech Stack

* **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
* **Clustering Models:** KMeans, Agglomerative, DBSCAN
* **Streamlit** – Interactive UI for clustering app
* **Pickle** – Model & scaler saving/loading

---

## 🚀 Results & Insights

* **Agglomerative Clustering** gave the **best silhouette score**, hence used as the final model.
* Countries were grouped into **natural clusters** based on development indicators.
* The clusters help identify **developed, developing, and underdeveloped** groups.

---

## 📌 Future Enhancements

* 🌐 Add **geospatial visualizations** (world map clustering)
* 📈 Extend with **time-series data** to track development trends over time
* 🔍 Deploy app on **Cloud (Heroku / Streamlit Cloud)** for public access

---
