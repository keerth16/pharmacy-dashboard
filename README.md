# 💊 Pharmacy Dashboard
This Pharmacy Dashboard is a full-featured web application designed to help pharmacies manage operations efficiently. It includes modules for prescription tracking, doctor and patient management, medicine inventory, and visual analytics — all accessible through a user-friendly dashboard.The dashboard was developed using real sales data from **Tamilnadu Co-operative Pharmacy**, Madurai.

---

## 🏪 Business Context

- **Pharmacy Name:** Tamilnadu Co-operative Pharmacy  
- **Location:** East Veli Street, Madurai, Tamil Nadu  
- **Objective:** Optimize inventory, forecast demand, reduce wastage, and enhance strategic decisions using data insights.

---

## 📊 Key Objectives

- Identify sales and prescription trends.
- Predict future demand and stock requirements.
- Classify near-expiry medicines to reduce loss.
- Improve operational efficiency using data-driven methods.

---

## 📥 Data Collection

- **Source:** [Tamil Nadu Co-operative Medical Stores Portal](#)  
- **Duration:** October 2024 – February 2025  
- **Method:** Bills were downloaded as PDFs and parsed using Python libraries (`PyPDF2`, `pdfplumber`).

### Sample Data Fields

- Bill Number, Date  
- Doctor & Patient Name  
- Medicine Name & Manufacturer  
- Quantity, Expiry, Price, GST, Discount  
- Total Payment  

> 📄 [Sample Dataset Link](#)

---

## 🧹 Data Preprocessing

- Removed noisy characters and standardized formats.
- Converted data types for accurate analysis.
- Handled missing values and duplicates.
- Validated extracted data against original PDFs.

---

## 📈 Analytical & Statistical Methods

- **Doctor-wise Prescription Pattern** – Most frequently prescribed medicines by each doctor.  
- **Hypothesis Testing on Bill Amounts** – Detect billing anomalies.  
- **Pareto Analysis (80/20 Rule)** – Identify top patients driving sales.  
- **Correlation: Quantity vs Discount** – Understand discount impact on sales.  
- **Cohort Analysis** – Group and analyze patient retention.  
- **Product Life Cycle Curve** – Identify medicine demand phases.  
- **RFM Analysis** – Segment patients using Recency, Frequency, and Monetary value.  
- **Restock Logic** – Recommend stock refills based on sales trends.

---

## 🤖 Prediction Models

| Model | Purpose |
|-------|---------|
| **ARIMA** | Forecast future sales trends |
| **SARIMA** | Capture seasonal demand patterns |
| **Random Forest Classifier** | Predict medicine expiry status |
| **Adherence Prediction** | Detect patients likely to stop medication |

---

## 📊 Power BI Dashboard

The Power BI dashboard brings all analysis and predictions together with:

- 📍 Interactive filtering and drill-down
- 📈 Real-time sales monitoring
- 🧾 Stock-level alerts
- 🩺 Doctor-prescription tracking
- 🔮 Predictive insights for planning

> 🔗 [View Power BI Dashboard](#)

---

## 🧑‍💻 Code & Tools Used

**Languages & Platforms:**  
- Python  
- Power BI  

**Python Libraries:**  
- `PyPDF2`, `pdfplumber` – PDF parsing  
- `pandas`, `numpy` – Data preprocessing and analysis  
- `matplotlib`, `seaborn` – Visualizations  
- `statsmodels` – ARIMA, SARIMA models  
- `scikit-learn` – Random Forest Classification  

---

## ✅ Outcomes

- ⚠️ Reduced medicine expiry loss through predictive classification.
- 📦 Improved inventory management using forecast-based restocking logic.
- 🔍 Identified valuable trends in prescription and patient behavior.
- 💡 Enabled data-driven decision-making for pharmacy operations.

---

## ✍️ Blog Post

> 📖 Read the full blog: [Pharmacy Sales and Inventory Analytics Using Power BI](#)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


