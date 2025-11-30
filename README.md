# First-report
Analysis to reasons of Manufacturing Downtime 

# 📊 **Analyze Manufacturing Downtime**

---

## 🔍 **Executive Summary**

This project integrates **Business Intelligence (BI)** and **Data Science** to analyze manufacturing downtime and improve production efficiency.
By combining real-time dashboards, predictive forecasting, and automated insights, the project identifies root causes of downtime and estimates future production performance.
The results support operational optimization, proactive maintenance, and better decision-making.

---

## 📖 **Table of Contents**

* [Project Objectives](#-project-objectives)
* [Dataset Overview](#-dataset-overview)
* [Technologies & Tools](#-technologies--tools)
* [Methodology](#-methodology)
* [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
* [Project Timeline & Milestones](#-project-timeline--milestones)
* [Deliverables](#-deliverables)
* [Roles & Responsibilities](#-roles--responsibilities)
* [Setup & Execution Guide](#-setup--execution-guide)
* [Future Enhancements](#-future-enhancements)
* [Contact Information](#-contact-information)
* [Contributions & Support](#-contributions--support)
* [Copyright & Licensing](#-copyright--licensing)

---

## 🏆 **Project Objectives**

* **Identify the main factor causing production downtime** to determine which issues have the highest overall impact on operational efficiency.
* **Estimate how many batches are expected to be produced tomorrow** to support planning and resource distribution.
* **Determine the top 5 reasons for production downtime** based on both frequency and downtime duration.
* **Measure how much downtime is caused by operator errors compared to other factors** to highlight areas for training and performance improvement.
* **Identify which actuators or products cause the most downtime** to guide targeted maintenance and product-level optimization.

---

## 📁 **Dataset Overview**

**Source:** **Source:** [Google Sheets Dataset](https://docs.google.com/spreadsheets/d/1syIV6gtln4EUPynT3T1I0cMKLzN0z8oz/edit?usp=sharing)

**Volume:** Several thousand records across four integrated files

### **Main Files**

* `line_productivity.csv` → Production logs (date, product, operator, start/end time)
* `products.csv` → Product info (name, flavor, size, minimum batch time)
* `line_downtime.csv` → Downtime events (time, factor, batch)
* `downtime_factor.csv` → Categorized downtime reasons

**Purpose:**
To analyze efficiency, determine root downtime causes, and forecast future downtime behavior.

---

## 🛠 **Technologies & Tools**

| Functionality              | Tools                |
| -------------------------- | -------------------- |
| **Business Intelligence**  | Power BI |
| **Programming & Analysis** | Python               |
| **Storage**                | Google Cloud / Local |
| **Version Control**        | Git & GitHub         |

---

## 🔬 **Methodology**

### **1️⃣ Data Integration & Preparation**

* Import four datasets
* Clean, merge, and validate records
* Feature engineering for downtime, operator efficiency, and batch performance

### **2️⃣ Business Intelligence**

* Interactive dashboards in **Power BI**
* Insights:

  * Downtime by product/operator
  * Error-related delays
  * Drill-down by batch, date, and factor

### **3️⃣ Forecasting & Modeling**

* Predict **downtime probability for next day**
* Estimate **next day expected batches**
* Use Python machine learning models

### **4️⃣ Automation**

* Auto-refresh dashboards
* Alerts for high downtime trends
* Scheduled data pulling from Google Sheets / Cloud

---

## 📊 **Key Performance Indicators (KPIs)**

* **Main Downtime Cause**

* **Predicted Production Breakdowns (Next Day)**

* **Expected Number of Batches (Next Day)**

* **Top 5 Downtime Reasons**

* **Operator Error Downtime (%)**

* **Downtime by Actuator / Product**

---

## 📅 **Project Timeline & Milestones**

| Phase                                 | Description                    | Duration        |
| ------------------------------------- | ------------------------------ | --------------- |
| **Phase 1 – Data Cleaning**           | Gather + clean + validate data | Oct 18 – Oct 22 |
| **Phase 2 – BI Dashboards**           | Power BI & Tableau             | Oct 23 – Oct 28 |
| **Phase 3 – Forecasting Models**      | Python ML models               | Oct 29 – Nov 3  |
| **Phase 4 – Integration & Reporting** | Automation + final report      | Nov 4 – Nov 10  |

---

## 🚀 **Deliverables**

* Cleaned dataset
* Power BI dashboards
* Python forecasting model
* Automated reporting system
* Final documentation and recommendations

---

## 👥 **Roles & Responsibilities**

| Role              | Member      | Tasks                                   |
| ----------------- | ----------- | --------------------------------------- |
| **Data Science**  | Sara, Eman  | Predictive modeling & downtime analysis |
| **Programming**   | Hanan       | Python scripts & integrations           |
| **Visualization** | Nermine | Power BI dashboard design & insights    |

---

## ⚙️ **Setup & Execution Guide**

### **Clone the Repository**

```bash
git clone https://github.com/yourrepo/project.git

```
