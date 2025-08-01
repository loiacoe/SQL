# 🗃️ SQL Projects with Google Cloud Public Datasets

This repository contains a collection of Jupyter Notebooks that explore real-world datasets using SQL, with queries executed on **Google Cloud BigQuery**.

The notebooks are designed for learning and practicing SQL in a practical, hands-on way, using publicly available datasets provided by Google Cloud.

---

## 📚 Contents

Each notebook covers a different dataset or SQL concept. Notebooks include:

- **🚕 NYC Taxi Dataset**  
  A complete notebook mixing SQL and Python for time-based aggregations, fare analysis, trip distance, and passenger trends using `bigquery-public-data.new_york_taxi_trips`.

- **💬 StackOverflow Dataset**  
  Querying developer questions, tag frequencies, and post popularity using `bigquery-public-data.stackoverflow`.

- **🇺🇸 USA Names Dataset**
  A complete notebook mixing SQL and Python for analysis and visualization of baby name trends using `bigquery-public-data.usa_names.usa_1910_2013`.

- **👶 Sample Natality Dataset**  
  Exploring birth statistics across U.S. states using `bigquery-public-data.samples.natality`. Topics include average birth weight, delivery trends by method, and birth count distributions by year and region.

---

## ☁️ How to Run

You can open and run these notebooks in **Google Colab** with BigQuery integration enabled.

### Setup (in Colab)
1. Authenticate your Google account:
   ```python
   from google.colab import auth
   auth.authenticate_user()


2. Run the notebook

---

## 🔧 Technologies Used

- **SQL** (Standard + BigQuery)  
- **Google BigQuery**  
- **Jupyter / Colab Notebooks**  
- **Python**, including:
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`

