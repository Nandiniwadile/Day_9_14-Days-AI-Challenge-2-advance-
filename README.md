---

# 📌 Day 9 – Recommendation System Visualization (README Text)

## 🎯 Objective

The goal of Day 9 was to build a **Recommendation System** using ALS (Alternating Least Squares) and generate Top-5 product recommendations for each customer.

---

## 🔹 Step 1: Rating Mapping

We created a rating dataset using:

* `customerID` → User
* `productIndex` → Item
* `quantity` → Rating

This converts transaction data into a **user-item interaction matrix** required for collaborative filtering.

---

## 🔹 Step 2: Train ALS Model

We trained an ALS model with:

* `userCol = customerID`
* `itemCol = productIndex`
* `ratingCol = rating`
* `coldStartStrategy = "drop"`

ALS learns hidden patterns between customers and products using **collaborative filtering**.

---

## 🔹 Step 3: Generate Top-5 Recommendations

After training, we generated:

* Predicted ratings for products
* Ranked products per customer
* Selected Top-5 highest predicted products

Final Output Columns:

* `customerID`
* `productIndex`
* `prediction`
* `rank`

---

# 📊 Visualization (Day 9)

### 1️⃣ Bar Chart – Top 5 Recommendations

This visualization shows:

* X-axis → Product Index
* Y-axis → Predicted Rating
* Each bar → Strength of recommendation

It helps understand which products the model recommends most strongly.

---

### 2️⃣ Distribution Plot – Prediction Scores

This plot shows:

* Distribution of predicted ratings
* Model confidence level
* Whether predictions are spread or concentrated

---

# 💡 What This Visualization Proves

✔ Model successfully trained
✔ Recommendations generated per user
✔ Ranking logic working
✔ Model prediction strength visible

---

# 🏆 Day 9 Status

✅ Rating Mapping Created
✅ ALS Model Trained
✅ Top-5 Recommendations Generated
✅ Visualization Completed

---


