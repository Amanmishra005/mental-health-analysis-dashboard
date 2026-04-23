# 🧠 Mental Health Analysis Dashboard (2020–2024)

## 📌 Overview

This project presents a comprehensive analysis of mental health trends in the United States using the CDC Household Pulse Survey dataset (2020–2024).

It combines **Exploratory Data Analysis (EDA)**, **data visualization**, and a **lightweight dashboard** to uncover patterns in anxiety and depression across different demographic groups.

---

## 🎯 Objectives

* Analyze trends in **Anxiety**, **Depression**, and **combined indicators**
* Identify **high-risk demographic groups**
* Study **temporal changes (2020–2024)**
* Build a **clean and simple dashboard** for visualization

---

## 📊 Dataset

* Source: CDC Household Pulse Survey
* Records: ~16,000+
* Attributes:

  * Time Period
  * Indicator (Anxiety, Depression)
  * Demographic Groups
  * Subgroups (Age, Sex, Education, etc.)
  * Prevalence Value (%)
  * Confidence Intervals

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Panel (for dashboard)

---

## 🔄 ETL Process

* Data Cleaning:

  * Removed missing values (~4%)
  * Dropped irrelevant columns (Quartile Range)
* Feature Engineering:

  * Extracted **Year** from date
  * Created simplified indicator labels
* Data Transformation:

  * Groupby aggregations
  * Mean prevalence calculations

---

## 📈 Key Insights

### 📌 1. National Trends

* Mental health issues peaked during **2020–2021 (COVID period)**
* Gradual decline observed by **2024**

### 📌 2. Age-Based Analysis

* Highest prevalence: **18–29 years (~48%)**
* Lowest prevalence: **80+ years (~17%)**

### 📌 3. Gender Insights

* Females show **higher anxiety & depression rates** than males

### 📌 4. Education Impact

* Lower education → **higher mental health issues**
* Higher education → **lower prevalence**

### 📌 5. Disability Impact

* Individuals with disabilities show **2× higher prevalence**

---

## 📊 Visualizations Included

* 📈 Line Plot (Trend Over Time)
* 📊 Bar Charts (Demographics)
* 📉 Horizontal Bar Charts (Age Analysis)
* 🔥 Heatmap (Education vs Indicator)
* 📌 Missing Value Analysis

---

## 🖥️ Dashboard Features

* Clean and simple UI
* Year-wise trend visualization
* Age group comparison
* Lightweight (no lag, optimized performance)

---

## 📂 Project Structure

```
Mental-Health-Analysis/
│
├── mental_health_dataset.csv
│
├── images/
│   ├── dashboard.png
│   ├── trend.png
│   ├── age_analysis.png
│   └── heatmap.png
│
├── notebook/
│   └── CA2Project.ipynb
│
├── report/
│   └── Mental_Health_Analysis_Report.docx
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Run `CA2Project.ipynb`

---

## 📌 Future Improvements

* Add machine learning models (prediction)
* Deploy dashboard using Streamlit
* Add more interactive filters
* Integrate real-time data

---

## 👨‍💻 Author

**Aman Mishra**
B.Tech CSE
Lovely Professional University

---

## 📜 License

This project is for academic purposes.
