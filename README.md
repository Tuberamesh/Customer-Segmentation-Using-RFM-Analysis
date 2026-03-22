# Customer Segmentation Using RFM Analysis

## 📖 Project Overview
This project focuses on **customer segmentation** using **RFM (Recency, Frequency, Monetary) analysis** to understand customer purchasing behavior and support data-driven marketing decisions.

The analysis is performed on a real-world online retail dataset containing over **500,000 transactions**.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- Jupyter Notebook

---

## 📂 Dataset
The dataset contains transaction-level data including:

| Column Name     | Description                              |
|-----------------|------------------------------------------|
| InvoiceNo       | Unique invoice number                     |
| CustomerID      | Unique customer identifier                |
| Quantity        | Number of items purchased                 |
| UnitPrice       | Price per item                            |
| InvoiceDate     | Date of transaction                       |
| Country         | Customer's country                         |

**CSV final Dataset:** [Download CSV](https://github.com/Tuberamesh/Customer-Segmentation-Using-RFM-Analysis/blob/main/rfm_customer_segmentation.csv)

---

## 🔍 Methodology

### 1️⃣ Data Cleaning
- Removed missing Customer IDs
- Filtered invalid transactions (negative quantity & price)
- Converted date columns to datetime format
- Created a **Revenue** feature

### 2️⃣ RFM Analysis
- **Recency**: Days since last purchase  
- **Frequency**: Number of unique purchases  
- **Monetary**: Total revenue per customer

### 3️⃣ Customer Segmentation
- Used **quantile-based scoring**  
- Segmented customers into meaningful groups such as:
  - Champions
  - Loyal Customers
  - At Risk
  - Hibernating

---

## 📊 Output
- Final customer-level RFM dataset exported as **CSV**  
- [View CSV file](https://github.com/Tuberamesh/Customer-Segmentation-Using-RFM-Analysis/blob/main/rfm_customer_segmentation.csv)

- Analysis performed in Jupyter Notebook:  
- [View Notebook](https://github.com/Tuberamesh/Customer-Segmentation-Using-RFM-Analysis/blob/main/rfm_analysis.ipynb)

- Main Raw data set  **CSV**
- [Raw CSV](https://github.com/Tuberamesh/Customer-Segmentation-Using-RFM-Analysis/blob/main/Desktop/RFM/online_retail.csv)

---

## 🎯 Key Insights

- **Champions (26.3% of customers)** generated **£5.9M in revenue** — the highest value segment and top priority for retention and loyalty campaigns
- **41.1% of customers fall in "Others"** — a mixed group that needs further targeting; personalized re-engagement campaigns could unlock significant hidden revenue
- **At-Risk customers (6.3%)** were once frequent buyers but have gone inactive — with £431K in past spend, winning them back is a high-ROI opportunity
- **New Customers (7.4%)** show recent activity but low frequency — ideal targets for onboarding campaigns and cross-selling to increase lifetime value
- **Loyal Customers (18.9%)** contributed £1.35M — second highest revenue segment, strong candidates for upselling to Champion status

---

## 🚀 Future Enhancements
- Build interactive dashboards using Tableau / Power BI
- Apply clustering algorithms (K-Means) for advanced segmentation
- Automate analysis pipeline for repeated use

---

## 📎 Project Files
| File | Link |
- [Jupyter Notebook](https://github.com/Tuberamesh/Customer-Segmentation-Using-RFM-Analysis/blob/main/rfm_analysis.ipynb)
- [Processed CSV](https://github.com/Tuberamesh/Customer-Segmentation-Using-RFM-Analysis/blob/main/rfm_customer_segmentation.csv)
- [Raw CSV](https://github.com/Tuberamesh/Customer-Segmentation-Using-RFM-Analysis/blob/main/Desktop/RFM/online_retail.csv)






