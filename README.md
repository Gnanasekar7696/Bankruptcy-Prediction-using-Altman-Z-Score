# 🏦 Bankruptcy Prediction using Altman Z‑Score

## 📌 Objective

Use financial ratios to assess a company’s bankruptcy risk using the Altman Z‑Score model.

## 🧠 Model Description

Z = 1.2A + 1.4B + 3.3C + 0.6D + 1.0*E

Where:

A = Working Capital / Total Assets

B = Retained Earnings / Total Assets

C = EBIT / Total Assets

D = Market Value of Equity / Total Liabilities

E = Sales / Total Assets


## 🧾 Dataset

Financial statement data for multiple companies.

Required columns: Working Capital, EBIT, RE, Assets, Liabilities, Market Cap, Sales.


## ✅ Output

Z‑Score for each company.

Risk classification:

Z < 1.81 → High Risk

1.81 ≤ Z < 2.99 → Grey Zone

Z ≥ 2.99 → Safe

## 🛠 Tools

Python, pandas

## 📊 Business Use

Early warning tool for credit analysts, investors, and portfolio managers.

Enhances exposure monitoring for B2B or vendor risk management.
