# 📊 Online Retail EDA Project (Python)

## 🧭 Project Overview  
This project performs an **Exploratory Data Analysis (EDA)** on the **Online Retail II Dataset** from the **UCI Machine Learning Repository**.  
Using **Python and Google Colab**, the analysis explores **customer behavior, product performance, and revenue trends** through data cleaning, visualization, and feature engineering.

---

## 🌟 Project Goals  
- Understand customer purchase patterns and top-selling products  
- Handle missing values, duplicates, and incorrect entries  
- Analyze sales by **time, country, and product**  
- Generate **business insights** for decision-making  

---

## 👥 Stakeholders & Business Questions  

### **Stakeholders**
- 🧑‍💼 **Business Manager / CEO** – Focused on overall sales performance and revenue growth  
- 📦 **Inventory Team** – Tracks product demand and seasonal patterns  
- 📈 **Sales & Marketing Team** – Understands customer behavior for promotions  
- 💾 **Data Team** – Maintains clean, structured datasets for analysis  

### **Key Questions**
| Stakeholder | Questions |
|--------------|------------|
| **CEO** | Which products and customers bring the most revenue? Are sales growing over time? |
| **Inventory Team** | Which items sell the most? Are there seasonal peaks or returns? |
| **Data Team** | Are there missing or inconsistent values? What features can improve analysis? |
| **Marketing Team** | Who are the top buyers? How do sales differ by country and season? |

---

## 📊 EDA Questions  
1. How many unique customers are there? Who are the top customers by total purchases?  
2. How does sales vary across different countries? Which countries contribute the most to revenue?  
3. Are there seasonal trends in sales? How does `InvoiceDate` affect monthly or daily patterns?  
4. Which products and customers generate the highest revenue?  
5. Which `StockCode` or `Description` products are sold the most?  
6. How is `Quantity` distributed? Are there negative or outlier values?  
7. Are there missing values or duplicate entries affecting data accuracy?  

---

## 🧮 Dataset Overview  

| Column | Description |
|---------|-------------|
| **Invoice** | Transaction number |
| **StockCode** | Product code |
| **Description** | Product name |
| **Quantity** | Number of items purchased (negative = returns) |
| **InvoiceDate** | Date of transaction |
| **UnitPrice** | Price per product |
| **CustomerID** | Unique customer ID |
| **Country** | Country of purchase |

📊 **Rows:** ~1 Million  
📚 **Source:** [UCI Online Retail II Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail+ii)  
📦 **Kaggle Mirror:** [Online Retail II – UCI](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)

---

## ⚙️ Tools & Libraries  
- 🐍 **Python 3**  
- ☁️ **Google Colab**  
- 🧩 **pandas**, **numpy** – Data cleaning & analysis  
- 📈 **matplotlib**, **seaborn** – Data visualization  
- ⏰ **datetime** – Time-based feature extraction  

---

## 🧩 Project Workflow  

| Step | Description |
|------|-------------|
| **1. Data Loading** | Imported dataset and explored structure |
| **2. Data Cleaning** | Removed duplicates, handled missing values, fixed data types |
| **3. Feature Engineering** | Created new columns like `Revenue`, `Month`, `Weekday` |
| **4. EDA** | Analyzed product, customer, and sales trends |
| **5. Visualization** | Built charts for products, countries, and time trends |
| **6. Insights** | Summarized findings and business recommendations |
| **7. Documentation** | Added Markdown reports and final README for GitHub |

---

## 📈 Key Findings & Insights  

- 💰 **Revenue:** UK contributed the most revenue; sales peaked during **November–December**  
- 📦 **Products:** A few top products made up most of total sales  
- 👥 **Customers:** Repeat buyers contributed heavily to total revenue  
- 🌍 **Countries:** UK dominated, while **Germany and France** showed potential growth  
- 📆 **Trends:** Sales highest in **Q4**, lowest during summer  
- ⚠️ **Data Quality:** Negative quantities and missing `CustomerID`s were identified and cleaned  

---

## 💡 Business Insights & Conclusions  

- Focus on **high-revenue products** and **top customers**  
- Plan **holiday-season campaigns** to boost sales  
- Encourage **guest users** to register for loyalty programs  
- Improve **inventory planning** using demand forecasts  
- Maintain **clean data** pipelines for reliable insights  

---

## 📊 Visualizations  

- 📉 Quantity & Price Distributions *(Histogram, Boxplot)*  
- 🏆 Top Products & Countries *(Bar Charts)*  
- 📆 Monthly Revenue Trends *(Line Chart)*  
- 🔥 Correlation Heatmap  
- 🔗 Pairplots for Quantity, Price & Revenue  

<p align="center">
  <img width="952" height="412" alt="line_chart_EDA" src="https://github.com/user-attachments/assets/27130379-6147-4aa4-ba8f-da73a151b016" />
  <img width="1282" height="425" alt="Boxplot_EDA" src="https://github.com/user-attachments/assets/e1cee76d-afeb-417d-842f-9ff07669b716" />
  <img width="1080" height="429" alt="Bar_Plot_EDA" src="https://github.com/user-attachments/assets/1545ab11-794d-48b5-83b4-8477a2be72dc" />
</p>

---

## 🗂️ Repository Structure  

```
Online-Retail-EDA-Project/
│
├── dataset/ # Raw CSV dataset (online_retail_ii_UCI_data_set.csv)
│
├── notebooks/ # Jupyter/Colab notebooks
│ ├── Online_Retail_EDA.ipynb
│
├── reports/ # Insights, visualizations, and conclusions
│ ├── EDA_Summary.md
│ ├── Key_Insights.md
│
├── images/ # Graphs and visual snapshots
│ ├── line_chart_EDA.png
│ ├── boxplot_EDA.png
│ ├── barplot_EDA.png
│
├── README.md # Project documentation
└── LICENSE # License information
```


---

## 🛠️ How to Run the Project  

1. Open **`Online_Retail_EDA.ipynb`** in **Google Colab** or Jupyter Notebook  
2. Upload the dataset: `online_retail_ii_UCI_data_set.csv`  
3. Run all cells sequentially  
4. The cleaned dataset will be saved as **`online_retail_cleaned.csv`**  

---

## 👨‍💻 Author  

**A. Sai Arvind**  
📊 *Data Analyst | Python | Power BI | Excel | SQL*  

📧 **Email:** saiarvind5081@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/saiarvindofficial/
🔗 **GitHub:** https://github.com/Sai-Arvind

---

⭐ **If you liked this project, please give it a star and follow for more!** ⭐
