# 🍽️ Restaurant Data Analysis & Machine Learning Project

## 📌 Overview

This project focuses on analyzing restaurant data to extract meaningful insights using **Data Analysis, Visualization, and Machine Learning techniques**.

The goal is to understand patterns in restaurant ratings, cuisines, pricing, and locations, and build a predictive model for restaurant ratings.

---

## 🚀 Key Features

### 🔹 Data Preprocessing

* Data loading and cleaning
* Handling missing values
* Feature engineering
* Cuisine data transformation

---

### 🔹 Exploratory Data Analysis (EDA)

* Top cuisines analysis
* Price range distribution
* Rating distribution
* Votes vs rating relationship
* Correlation heatmap

---

### 🔹 City-Based Analysis

* City with highest number of restaurants
* Average rating per city
* Best-rated city
* Top cities visualization

---

### 🔹 Advanced Analysis

* Cuisine combination trends
* Restaurant chain detection
* Geographical map visualization
* Review analysis using NLP (WordCloud)

---

### 🔹 Machine Learning Models

* Linear Regression
* Random Forest Regressor

#### 📊 Model Performance:

* **Random Forest R² Score:** 0.93
* **Mean Squared Error (MSE):** 0.15

👉 Random Forest performed significantly better than Linear Regression.

---

## 📊 Visual Outputs

The project generates multiple visualizations:

* Top Cuisines Bar Chart
* Price Distribution Graph
* Rating Histogram
* Votes vs Rating Scatter Plot
* Correlation Heatmap
* City Analysis Graph

📍 Interactive Map:

* Restaurant locations visualized using Folium
* Saved as: `outputs/map.html`

---

## 🖥️ Interactive Dashboard

A live dashboard is built using **Streamlit**.

### ▶️ Run Dashboard:

```bash
streamlit run app.py
```

---

## ⚙️ Installation

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 📂 Project Structure

```
Data-Analysis-Project/
│── data/
│   └── Dataset.csv
│
│── outputs/
│   ├── graphs/
│   └── map.html
│
│── src/
│   ├── preprocessing.py
│   ├── visualization.py
│   ├── model.py
│
│── app.py
│── main.py
│── requirements.txt
│── README.md
│── screenshots/
```

---

## 📸 Screenshots

### 📊 Graphs

(Add your graph screenshots here)

### 🗺️ Map Visualization

(Add map screenshot here)

### 📈 Dashboard

(Add Streamlit dashboard screenshot here)

---

## 📌 Key Insights

* **New Delhi** has the highest number of restaurants
* Some cities have higher average ratings despite fewer restaurants
* Strong correlation observed between **votes and ratings**
* Popular cuisines include combinations like **North Indian + Chinese**
* Chain restaurants dominate in urban areas

---

## 🎯 Conclusion

This project demonstrates a complete **Data Science workflow**, including:

* Data Cleaning
* Exploratory Analysis
* Visualization
* Machine Learning
* Dashboard Development

It provides actionable insights into restaurant trends and customer preferences.

---

## 👨‍💻 Author

**Vivek Shukla**
Diploma CSE Student
