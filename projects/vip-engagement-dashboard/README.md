# VIP Engagement Forecasting & Automation Dashboard

## 📌 Overview
This project focuses on automating the tracking, classification, and analysis of VIP guest behavior to improve repeat business, personalize service outreach, and support strategic decision-making.

> **Note:** The original dataset is proprietary. This case study outlines the structure, logic, workflow, and analytics approach used. A simulated dataset can be added later for public demonstration.

---

## 🎯 Project Objectives
- Identify and classify high-value VIP guests using automated logic.
- Track engagement touchpoints and service interactions over time.
- Forecast repeat stay likelihood using historical trends.
- Provide leadership with clear, visual dashboards for outreach and retention.

---

## 🧰 Tools & Technologies
- **Excel (Advanced)** – formulas, PivotTables, data modeling  
- **VBA Macros** – automated data ingestion and classification  
- **Power BI** – dashboard visualization  
- **ETL Concepts** – data cleaning, merging, structure design

---

## 🔧 Process & Methodology

### **1. Data Collection & Preparation**
- Consolidated exports from PMS, loyalty program systems, and service logs.
- Cleaned and standardized:
  - Guest IDs  
  - Date formats  
  - Spend values  
  - Stay frequency metrics  
- Created derived fields:
  - Total stays  
  - Stay frequency score  
  - Last visit date  
  - VIP tier classification  

---

### **2. Automated VIP Classification (Excel + VBA)**
Automation logic included:

- Assigning VIP tiers based on custom business rules (e.g., total spend, frequency, loyalty level).  
- Using macros to:
  - Refresh raw data tables  
  - Recalculate guest classifications  
  - Output an updated, cleaned dataset used by Power BI  

This eliminated manual data upkeep and ensured accuracy.

---

### **3. Dashboard Development (Power BI)**
The dashboard included:

#### **Key Visuals**
- VIP count by tier  
- Engagement trend over time  
- Repeat stay frequency distribution  
- VIPs at risk (time since last stay)  
- Breakdown of VIP amenities, upgrades, and touchpoints  

#### **Filters**
- Date range  
- Tier  
- Segment  
- Stay type  
- Loyalty attributes  

---

## 📈 Results & Impact
- Leadership could instantly see which guests required outreach.  
- Improved accuracy and consistency of VIP tracking.  
- Enabled targeted, tier-specific engagement strategies.  
- Contributed to a measurable increase in **repeat VIP stay behavior**.  

---

## 🔮 Potential Enhancements
- Migrate logic to Power BI or Python for fully automated ETL.  
- Add predictive modeling (probability of next visit).  
- Integrate with CRM for automated email sequences.  
- Include segmentation based on behavior clusters or spend patterns.

---

## 📂 Folder Contents (Suggested)
