

---

# 🚀 14 Days AI Challenge – Databricks ML Pipeline Project

## 📌 Project Overview

This project demonstrates a complete end-to-end Machine Learning pipeline built on **Databricks + PySpark**.

It includes:

* Feature Engineering
* Model Training
* MLflow Experiment Tracking
* Batch Inference Pipeline
* Recommendation System (ALS)
* Workflow Pipeline Automation

This project simulates a **real-world production ML system**.

---

# 🏗️ Architecture Overview

1. Raw Transaction Data (Delta Table)
2. Data Processing & Feature Engineering
3. Model Training (Spark MLlib)
4. MLflow Tracking
5. Batch Predictions
6. Recommendation System (Collaborative Filtering)
7. Workflow Automation using Databricks Jobs

---

# 📅 Day-wise Implementation

---

## ✅ Day 6 – Model Training & Tuning

* Trained Logistic Regression
* Trained Random Forest
* Performed Hyperparameter Tuning
* Evaluated model using AUC
* Compared model performance

Technology Used:

* PySpark MLlib
* Spark DataFrame
* Evaluation Metrics

---

## ✅ Day 7 – MLflow Experiment Tracking

* Logged parameters
* Logged metrics
* Logged trained model
* Compared multiple experiment runs

Used:

* MLflow Tracking
* Experiment Versioning

---

## ✅ Day 8 – Batch Inference Pipeline

Tasks Completed:

1. Scored all users
2. Saved predictions to Gold Delta Table
3. Identified Top Predicted Buyers

Implemented:

* Batch scoring using trained model
* Delta Table storage
* Aggregation & ranking logic

---

## ✅ Day 9 – Recommendation System (ALS)

Built a Collaborative Filtering Model using ALS.

Steps:

1. Converted product names to numeric indices using StringIndexer
2. Created user-item rating mapping
3. Aggregated purchase history as implicit ratings
4. Trained ALS model
5. Generated Top-5 product recommendations per customer
6. Ranked recommendations using Window Functions

Concepts Covered:

* Collaborative Filtering
* User-Item Interaction Matrix
* Cold Start Handling
* Recommendation Ranking

---

# 🔄 Databricks Workflow Pipeline

All tasks are connected using **Databricks Workflows**.

Execution Flow:

Day 6 → Day 7 → Day 8 → Day 9

This simulates a production ML pipeline where:

* Models are trained
* Experiments tracked
* Predictions generated
* Recommendations produced

Automatically.

---

# 🛠️ Tech Stack

* Databricks
* Apache Spark
* PySpark
* Spark MLlib
* MLflow
* Delta Lake
* Python
* Matplotlib / Seaborn (Visualization)

---

# 📊 Key Learnings

* How real ML pipelines are built in industry
* Importance of experiment tracking
* Batch inference architecture
* Recommendation system implementation
* Workflow automation in Databricks

---

# 🎯 Project Outcome

This project demonstrates:

✔ End-to-end ML lifecycle
✔ Scalable data processing
✔ Model training & tracking
✔ Production-style recommendation system
✔ Automated workflow pipeline

---

# 🔗 Author

Nandini Wadile
B.Tech – Artificial Intelligence & Data Science
Aspiring Data Scientist / ML Engineer

---



