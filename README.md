# 📊 Blinkit Sales Data – End-to-End Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs a **complete Exploratory Data Analysis (EDA)** on a Blinkit (BigMart-style) retail dataset to understand **sales drivers, outlet performance, product characteristics, and customer demand patterns**.

The analysis follows a **structured data analytics workflow**:
- Data understanding
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Correlation analysis
- Business insights & recommendations

The goal is to derive **actionable business insights** using **Python-based EDA techniques**.

---

## 🧾 Dataset Description
The dataset contains **8,523 records** with **12 features**, representing product-level and outlet-level information.

### 🔹 Key Columns
- **Item Identifier** – Unique product ID  
- **Item Type** – Product category  
- **Item Fat Content** – Low Fat / Regular  
- **Item Visibility** – Shelf visibility metric  
- **Item Weight** – Product weight  
- **Sales** – Total sales value (Target Variable)  
- **Rating** – Product rating  
- **Outlet Identifier** – Store ID  
- **Outlet Type** – Grocery Store / Supermarket  
- **Outlet Size** – Small / Medium / Large  
- **Outlet Location Type** – Tier 1 / Tier 2 / Tier 3  
- **Outlet Establishment Year** – Store opening year  

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🔍 Analysis Workflow

### 1️⃣ Univariate Analysis
- Distribution of Sales, Item Weight, Item Visibility, Ratings
- Frequency analysis of categorical variables
- Identification of skewness and dominant categories

### 2️⃣ Bivariate Analysis
- Sales vs Item Fat Content
- Sales vs Outlet Type
- Sales vs Outlet Location Type
- Item Visibility vs Sales
- Item Weight vs Sales

### 3️⃣ Multivariate Analysis
- Sales comparison across Outlet Type & Outlet Size
- Sales trends across Fat Content & Outlet Type
- Bubble chart analysis using Visibility, Weight, and Sales

### 4️⃣ Correlation Analysis
- Correlation heatmap for numerical features
- Evaluation of linear relationships between sales drivers

---

## 📈 Key Insights
- Sales distribution is **right-skewed**, with few products driving most revenue  
- **Outlet Type and Outlet Size** have a strong impact on sales performance  
- **Item Visibility alone does not guarantee higher sales**  
- Regular-fat items generally outperform low-fat items  
- Tier 2 and Tier 3 locations show higher variability in sales  
- Numerical features show **weak correlation with sales**, indicating influence of multiple factors  

---

## 🎯 Business Recommendations
- Focus inventory and promotions on **high-performing product categories**
- Optimize **store layout and outlet strategy**, not just product visibility
- Prioritize expansion and marketing for **medium and large outlets**
- Re-evaluate low-performing items across all outlet types

---

## 📁 Project Structure

