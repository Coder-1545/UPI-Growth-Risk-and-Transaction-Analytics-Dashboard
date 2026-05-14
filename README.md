# 💳 UPI Growth, Risk & Transaction Analytics Dashboard

An interactive and insight-driven Power BI dashboard developed to analyze UPI growth trends, transaction behavior, system performance, and financial risk patterns using real-world Kaggle datasets. This project focuses on transforming raw digital payment transaction data into meaningful business insights through interactive visualizations, KPI reporting, and DAX-based analytics.

The dashboard was created as part of a Data Visualization & Management project to demonstrate how Business Intelligence tools can be used to analyze large-scale digital payment ecosystems and user transaction patterns.

---

# 📌 Project Overview

With the rapid rise of digital transactions and UPI-based payments in India, analyzing transaction patterns and financial risks has become increasingly important. This project aims to provide a centralized analytics solution that helps visualize payment growth trends, compare transaction methods, monitor system performance, and identify suspicious transaction activity.

The dashboard combines multiple analytical perspectives including:
- Executive-level KPI monitoring
- UPI growth and user behavior analysis
- Transaction performance evaluation
- Fraud and risk analysis
- Interactive filtering and comparative insights

The project was developed using Power BI and DAX with publicly available Kaggle datasets related to digital payment transactions and fraud detection.

---

# 🎯 Objectives of the Project

The primary objective of this project is to analyze and visualize digital payment trends using interactive dashboards and business intelligence techniques. The dashboard was designed to:
- Understand the growth and adoption of UPI transactions over time
- Analyze user transaction behavior and payment preferences
- Compare different digital payment methods
- Monitor transaction performance and operational efficiency
- Detect high-value and suspicious transactions
- Generate dynamic insights using KPI metrics and DAX calculations

---

# 🛠️ Tools & Technologies Used

| Tool / Technology | Purpose |
|------------------|---------|
| Power BI | Dashboard Development & Visualization |
| DAX | KPI Measures & Calculated Columns |
| Power Query | Data Cleaning & Transformation |
| Excel / CSV | Dataset Storage |
| Kaggle Datasets | Data Source |
| GitHub | Project Documentation & Hosting |

---

# 📂 Datasets Used

The project uses two publicly available datasets from Kaggle.

## 1️⃣ UPI Transactions 2024 Dataset
This dataset was used to analyze UPI growth trends, user transaction behavior, yearly transaction changes, and payment adoption patterns.

### Dataset Link
[UPI Transactions 2024 Dataset](https://drive.google.com/drive/folders/1meuDRgb06nFX1w0gueaUZdGjYMP85Kl-?usp=sharing)

---

## 2️⃣ Online Payments Fraud Detection Dataset
This dataset was used for fraud analysis, transaction risk identification, payment method comparison, and system performance monitoring.

### Dataset Link
[Online Payments Fraud Detection Dataset](https://drive.google.com/drive/folders/1P9kqOIEDCIAAvI_Cc4V0GZ-LvJ5nA4Ix?usp=sharing)

---

# 📊 Dashboard Structure

The dashboard consists of four interactive pages, each focusing on a different analytical aspect of the digital payment ecosystem.

---

# 🟦 Page 1 – Executive Summary Dashboard

The Executive Summary Dashboard provides a high-level overview of the overall digital payment ecosystem. This page was designed to give decision-makers a quick understanding of transaction activity, transaction value, user engagement, and payment success trends.

The top section of the dashboard contains KPI cards displaying:
- Total Transactions
- Total Transaction Value
- Total Users
- Success Rate

To visualize transaction activity over time, a line chart was used to display transaction trends across different periods. A donut chart was included to show the distribution of payment methods, helping users understand which payment modes contribute most to transaction activity.

A map visualization was also added to represent transaction distribution geographically. Interactive year-based slicers allow users to dynamically filter all visuals and observe how transaction behavior changes over time.

This page acts as the central overview page of the dashboard and provides a quick summary of the overall payment system.

---

# 🟩 Page 2 – UPI Growth & User Behavior Analysis

This page focuses specifically on understanding how UPI transactions evolved and became increasingly popular over the years. The goal of this page is to analyze user behavior and identify trends in digital payment adoption.

A line chart was used to represent year-wise UPI transaction growth, clearly highlighting the rapid increase in UPI usage after 2020. Monthly transaction trends were visualized using column charts to identify seasonal transaction behavior and fluctuations.

Payment method comparisons were included using bar and donut charts to compare UPI against other payment systems. KPI metrics such as:
- Year-over-Year (YoY) Growth Percentage
- Average Transaction Value
- Transactions per User

were calculated using DAX measures to provide deeper analytical insights.

Interactive slicers were implemented to allow users to dynamically explore trends for different years and payment methods. This page helps demonstrate the transformation of digital payments and increasing reliance on UPI-based systems.

---

# 🟥 Page 3 – Transaction Performance & System Analysis

The Transaction Performance & System Analysis page focuses on backend transaction reliability and operational performance. This page was designed to evaluate how efficiently the payment system handles transaction activity and identify potential performance-related concerns.

KPI cards were added to display:
- Success Rate
- Failure Rate
- Average Transaction Time

Fraud indicators from the dataset were used to simulate failed or risky transactions. Bar charts were created to compare failure rates across different transaction types and identify which transaction categories contribute most to system risk.

A histogram visualization was used to analyze transaction time distribution, helping identify slow or delayed transaction patterns. Additional tables were included to display high-value and potentially suspicious transactions.

An alert system and risk indicator were also added to help visualize system stability and identify unusual transaction behavior. This page demonstrates how Business Intelligence can be used to monitor transaction performance and operational efficiency in digital payment systems.

---

# 🟪 Page 4 – Payment Comparison & Risk Insights

The final page focuses on advanced analytical insights related to payment comparison, user behavior, and transaction risk analysis. This page combines comparative analytics with financial risk monitoring to create a more advanced and insight-driven dashboard experience.

Bar charts and donut charts were used to compare transaction volume across multiple payment methods and analyze market share contribution. Tables were added to identify top users and monitor high-value transactions.

Additional DAX measures were implemented to detect suspicious transactions based on transaction amount thresholds and fraud indicators. Repeat user analysis was also included to compare repeat users against new users and better understand user transaction patterns.

A gauge chart was designed to represent overall system risk levels based on suspicious and high-value transaction activity. Interactive slicers allow users to dynamically filter the dashboard by year, payment method, and other analytical categories.

This page serves as the advanced analytical section of the dashboard and highlights how data visualization techniques can be used for financial risk analysis and transaction intelligence.

---

# 🧮 DAX Measures Implemented

The dashboard includes multiple DAX measures ranging from beginner to intermediate level calculations. These measures were used to create KPIs, risk indicators, and analytical metrics.

Some of the implemented measures include:
- Total Transactions
- Total Transaction Value
- Total Users
- Success Rate
- Failure Rate
- YoY Growth Percentage
- Average Transaction Value
- Transactions per User
- High Value Transactions
- Risk Score Percentage

These calculations enabled dynamic and real-time analytical insights across the dashboard.

---

# 🎛️ Interactive Features

The dashboard was designed with interactive Business Intelligence features to improve user experience and analytical flexibility.

Implemented interactive features include:
- Dynamic slicers
- Cross-filtering visuals
- Interactive KPI updates
- Drill-down trend analysis
- Responsive chart filtering
- Dynamic risk analysis

All visuals respond dynamically based on slicer selections, creating a fully interactive dashboard experience.

---

# 📈 Key Insights Generated

The dashboard generated several meaningful insights related to digital payment systems and transaction behavior.

Some important observations include:
- Significant increase in UPI adoption after 2020
- Higher transaction activity for specific payment methods
- Presence of high-value transactions contributing to financial risk
- Rare but impactful fraudulent transactions
- Strong contribution from repeat users to overall transaction activity

These insights help demonstrate the value of data visualization and Business Intelligence techniques in understanding financial transaction ecosystems.

---

# 🚀 Future Enhancements

The dashboard can be further enhanced by integrating:
- Real-time payment APIs
- Machine Learning-based fraud prediction
- Live transaction monitoring
- Predictive analytics models
- Mobile responsive reporting
- Cloud-based deployment

These improvements would make the dashboard more scalable and production-ready.

---

# 📷 Dashboard Screenshots

## 🟦 Executive Summary Dashboard
![Executive Summary](screenshots/executive-summary-dashboard.png)

---

## 🟩 UPI Growth & User Behavior Analysis
![UPI Growth](screenshots/upi-growth-dashboard.png)

---

## 🟥 Transaction Performance & System Analysis
![Performance](screenshots/transaction-performance-dashboard.png)

---

## 🟪 Payment Comparison & Risk Insights
![Risk Analysis](screenshots/risk-analysis-dashboard.png)

---

# 📥 Power BI Dashboard File

Due to GitHub file size limitations, the complete Power BI dashboard file is shared through Google Drive.

### Power BI File Link
[Download Power BI Dashboard](https://drive.google.com/file/d/1zNxj5fg1sNWKvE7OcWMRoJvXMws7f9AX/view?usp=sharing)

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:
- Power BI dashboard development
- Data visualization techniques
- DAX calculations
- Business Intelligence reporting
- Interactive dashboard design
- Data transformation and cleaning
- Analytical storytelling
- KPI development and reporting

This project significantly improved my understanding of how analytical dashboards are designed for real-world financial systems.

---

# 👩‍💻 Author

**Kavya Huliyurdurga**

---

# 📌 Project Status

✅ Completed  
✅ Interactive Dashboard Developed  
✅ GitHub Documentation Added  
✅ Resume Project Ready
