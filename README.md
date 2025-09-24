# 📝 Data Analyst Self-Assessment Template

This project is a **self-assessment template for data analysts**, designed to practice exploratory data analysis (EDA), cleaning, aggregation, customer insights, and advanced analytics using **Python, Pandas, NumPy, and Matplotlib/Seaborn**.  

It uses a dataset with the following columns:  
`InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country`

---

## 📊 Sections of Analysis

### 1️⃣ Basic Exploration
- Inspect rows, columns, and data types  
- Check missing values  
- Identify unique countries  
- Find most frequent product descriptions  

### 2️⃣ Data Cleaning
- Remove missing `CustomerID` values  
- Filter out negative `Quantity` and `UnitPrice`  
- Standardize product descriptions (lowercase + strip spaces)  
- Drop duplicates  
- Convert `InvoiceDate` to datetime  

### 3️⃣ Aggregation & Summary
- Calculate total sales per transaction  
- Revenue by country  
- Top customers by revenue  
- Average quantity per product  
- Count invoices per customer  

### 4️⃣ Time-Based Analysis
- Monthly revenue trends  
- Weekly invoice counts  
- Identify the busiest sales day  
- First and last purchase dates per customer  
- Monthly revenue growth rate  

### 5️⃣ Customer Analysis
- Detect repeat customers  
- Build RFM (Recency, Frequency, Monetary) metrics  
- Segment customers into RFM groups  
- Find customers with highest **Average Order Value (AOV)**  
- Basic product co-occurrence (items bought together)  

### 6️⃣ Advanced Analysis
- Correlation between `Quantity` and `UnitPrice`  
- Detect outliers in pricing using IQR method  
- Visualize distribution of quantities sold (histogram)  
- Top products by revenue  
- Perform **cohort analysis** for monthly retention  

---

## 🚀 Key Features
- End-to-end **data cleaning + transformation + visualization**
- Ready-to-use **templates for common analytics tasks**
- Beginner to intermediate **practice roadmap**  
- Helps build **portfolio-ready analysis projects**  

---

## 📌 How to Use
1. Clone this repo  
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn
