# 🛡️ Bank Fraud Transaction Monitoring Dashboard

## 📌 Project Overview
This project presents an **end-to-end bank transaction monitoring dashboard** designed to analyse **transaction activity, detect potential fraud, and support operational oversight**. The dashboard provides a clear view of **transaction volume, success vs failure rates, fraud flags, network behaviour, and regional distribution**.

It is structured into three analytical layers:
1. **Transaction Overview**
2. **Fraud Detection Analysis**
3. **Transaction-Level Details**

---

## 🎯 Business Objectives
- Monitor real-time transaction performance
- Detect and analyse fraudulent transaction patterns
- Identify high-risk regions, network slices, and bandwidth groups
- Support investigation through transaction-level drill-downs
- Improve fraud response and operational decision-making

---

## 📊 Key KPIs
| Metric | Value |
|------|------|
| **Total Transactions** | 1,000 |
| **Total Transaction Amount** | $771.17K |
| **Successful Transactions** | 487 |
| **Failed Transactions** | 513 |
| **Fraudulent Transactions** | ~52% |
| **Non-Fraudulent Transactions** | ~48% |

---

## 🧠 Key Insights
- Transaction outcomes are nearly evenly split between **success and failure**, indicating potential system or risk issues.
- Over **half of transactions are flagged as fraudulent**, highlighting the need for tighter controls.
- Fraudulent activity is concentrated in specific **network slices and bandwidth groups**.
- Certain regions show **higher fraud density**, suggesting geographic risk clusters.
- **Transfers and withdrawals** contribute a larger share of fraud compared to deposits.
- Higher bandwidth ranges (e.g. **150–250 Mbps**) are associated with increased fraudulent transactions.

---

## 🖥️ Dashboard Structure & Features

### 1️⃣ Bank Transaction Report
- KPI cards for total transactions and amounts
- Transaction trend over time
- Breakdown by:
  - Transaction status
  - Fraud flag
  - Transaction type
- Global transaction distribution map
- Interactive filters:
  - Transaction type
  - Status
  - Device used
  - Network slice ID

---

### 2️⃣ Fraud Detection Analysis
- Fraudulent transactions by:
  - Bandwidth group
  - Network slice
  - Region
- Visual identification of high-risk technical configurations
- Drill-through capability for investigation

---

### 3️⃣ Transaction Details
- Transaction-level table including:
  - Transaction ID
  - Sender & receiver accounts
  - Transaction type
  - Amount
  - Fraud flag
  - Status
  - Bandwidth group
  - Network slice ID
  - Timestamp
- Conditional formatting to highlight fraud risk
- Full filtering and sorting for investigation workflows

---

## 🛠️ Tools & Skills Used
- **Power BI** (Data preparation, Dashboard design, DAX, drill-through)
- **Fraud Analytics**
- **Transaction Monitoring**
- **Operational Risk Analysis**
- **Geospatial Visualisation**
- **Data Storytelling for Risk & Compliance**

---

## 📂 Dataset
- Bank transaction records
- Transaction amounts and types
- Fraud flags
- Network and bandwidth metadata
- Device and regional attributes

---

## 📸 Dashboard Preview

### Bank Transaction Overview
<img src="https://github.com/EileenIp/Bank-Fraud-Transaction-Monitoring-Dashboard/blob/main/Bank%20Transaction%20Overview.png">

### Fraud Detection Analysis
<img src="https://github.com/EileenIp/Bank-Fraud-Transaction-Monitoring-Dashboard/blob/main/Fraud%20Detection%20Analysis.png">

### Transaction Details
<img src="https://github.com/EileenIp/Bank-Fraud-Transaction-Monitoring-Dashboard/blob/main/Transaction%20Details.png">

---

## 💼 Business Value
This dashboard enables banks and financial institutions to:
- Detect fraud patterns faster
- Prioritise high-risk transactions for investigation
- Improve network and security controls
- Reduce financial losses from fraudulent activity
- Support compliance and audit requirements

---

## 🚀 Future Enhancements
- Integrate machine learning fraud detection models
- Add real-time transaction streaming
- Implement anomaly detection thresholds
- Introduce fraud risk scoring
- Automate alerts for suspicious activity
