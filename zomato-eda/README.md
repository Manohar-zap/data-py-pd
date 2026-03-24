# 🍽️ Zomato Data Analysis (EDA Project)

## 📌 What this project does

This project analyzes a real Zomato dataset to understand what actually drives restaurant success — ratings, pricing, location, and services like online delivery.

Instead of just plotting graphs, the focus is on extracting patterns that make sense in real-world food business scenarios.

---

## 📂 Dataset Details

* Dataset: Zomato restaurants data
* Records: ~10,000+ entries (varies by version)
* Features include:

  * Restaurant Name
  * Location
  * Cuisines
  * Average Cost for Two
  * Ratings
  * Votes
  * Online Delivery / Table Booking

---

## 🛠️ Tech Stack

* Python
* Pandas (data handling)
* NumPy
* Matplotlib & Seaborn (visualization)
* Jupyter Notebook

---

## 🔧 Data Cleaning (Actual Work Done)

* Removed null values in ratings and cost columns
* Converted rating from string → float
* Cleaned inconsistent cuisine names
* Dropped duplicate records
* Standardized cost column

---

## 📊 Key Findings (Real Insights)

### 1. ⭐ Ratings vs Cost

* Expensive restaurants **don’t guarantee higher ratings**
* Mid-range restaurants (₹300–₹800) tend to perform better overall

---

### 2. 📍 Location Matters A LOT

* Certain areas have consistently higher-rated restaurants
* High competition zones → better average ratings

---

### 3. 🍜 Popular Cuisines

* North Indian, Chinese, and Fast Food dominate
* Multi-cuisine restaurants get more votes

---

### 4. 🚚 Online Delivery Impact

* Restaurants offering delivery:

  * Get **more votes**
  * Have slightly higher engagement

---

### 5. 📉 Low-rated Restaurants Pattern

* Usually:

  * Low votes
  * Poor location
  * No online delivery

---

## 📁 Project Structure

project-1/
│── Zomato Database Insights.ipynb
│── zomato_data.csv
│── README.md

---

## ▶️ How to Run

```bash
git clone <your-repo-link>
cd project-1
jupyter notebook
```

Open the notebook and run all cells.

---

## 🎯 What I learned

* Real datasets are messy — cleaning takes most time
* Visualization ≠ insight (you need interpretation)
* Small features like location & delivery can change outcomes

---

## 🚀 Next Steps

* Build a restaurant rating prediction model
* Create dashboard (Power BI / Tableau)
* Add recommendation system

---

## 💡 Why this project matters

This is not just plotting graphs — it shows how raw data can be turned into business insights, which is the core of data science.

