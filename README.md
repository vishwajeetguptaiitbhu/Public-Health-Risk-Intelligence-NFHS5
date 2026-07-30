# Public-Health-Risk-Intelligence-NFHS5
End-to-end Public Health Analytics project using Python, SQL, and Power BI to identify socioeconomic determinants of obesity through statistical modelling, population risk segmentation, and interactive business intelligence dashboards built on NFHS-5 microdata.

# 📊 Public Health Risk Intelligence: Obesity & Socioeconomic Determinants Analysis

An end-to-end Public Health Analytics and Business Intelligence project leveraging India's **National Family Health Survey (NFHS-5)** microdata (600,000+ records) to identify the socioeconomic and demographic determinants of obesity.

The project integrates **Python, SQL, and Power BI** to transform raw survey data into actionable insights through statistical modelling, population risk segmentation, and interactive decision-support dashboards.

---

## 🎯 Project Objectives

* Build a reproducible analytics pipeline for large-scale health survey data.
* Identify key demographic and socioeconomic determinants of obesity.
* Validate hypotheses using statistical inference and predictive modelling.
* Segment high-risk populations based on wealth, residence, age, and gender.
* Transform statistical findings into interactive business intelligence dashboards.
* Generate evidence-based insights for targeted public health interventions.

---

## 📂 Dataset

**Source:** National Family Health Survey (NFHS-5), India (IIPS)

**Records:** 600,000+ household members

### Variables Used

| Variable | Description |
|----------|-------------|
| Wealth Index Combined | Household wealth quintile (1–5) |
| Type of Place of Residence | Urban / Rural |
| Sex of Household Member | Male / Female |
| Age of Household Member | Age (Years) |
| Obesity | Binary Target Variable (0 = Non-Obese, 1 = Obese) |

---

# 🛠 Tech Stack

| Stage | Tools & Libraries |
|---------|------------------|
| Data Import | PyReadStat |
| Data Cleaning | Pandas, NumPy |
| Feature Engineering | Pandas |
| Exploratory Analysis | Matplotlib, Plotly |
| Statistical Analysis | SciPy, Statsmodels |
| Data Modelling | Logistic Regression |
| Database | SQL |
| Business Intelligence | Power BI |

---

# 🔄 Project Workflow

```text
NFHS-5 Survey Data (.sav)
        │
        ▼
Metadata Extraction
(PyReadStat)
        │
        ▼
Data Cleaning
(Pandas)
• Missing value treatment
• Variable selection
• Data validation
        │
        ▼
Feature Engineering
(Pandas)
• Obesity indicator
• Age grouping
• Variable transformation
        │
        ▼
Exploratory Data Analysis
• Distribution Analysis
• Crosstabs
• Demographic Profiling
        │
        ▼
Statistical Validation
(SciPy)
• Chi-square Test
• Confidence Intervals
        │
        ▼
Predictive Modelling
(Statsmodels)
• Binary Logistic Regression
• Wealth × Residence Interaction
• Sex × Residence Interaction
        │
        ▼
SQL Analytics Layer
• KPI Generation
• Population Segmentation
• Dashboard Views
        │
        ▼
Power BI Dashboard
• Executive KPIs
• Interactive Analysis
• Risk Segmentation
        │
        ▼
Policy & Decision Support Insights
```

---

# 🔬 Research Questions

1. Does obesity increase with household wealth?
2. Is obesity more prevalent in urban populations?
3. Does obesity differ significantly between males and females?
4. Does obesity increase with age?
5. Does the relationship between wealth and obesity differ between urban and rural populations?
6. Does residential setting modify gender differences in obesity?

---

# 📈 Statistical Methodology

### Data Preparation

* Data Cleaning
* Feature Engineering
* Variable Transformation
* Missing Value Handling

### Exploratory Analysis

* Frequency Distribution
* Crosstab Analysis
* Population Profiling

### Inferential Statistics

* Chi-square Test of Independence
* 95% Confidence Intervals

### Predictive Modelling

* Binary Logistic Regression
* Wealth × Residence Interaction Model
* Sex × Residence Interaction Model

---

# 📊 Key Findings

### 1. Socioeconomic Gradient

Obesity prevalence increased consistently across household wealth quintiles, indicating a strong positive socioeconomic gradient.

---

### 2. Urban-Rural Difference

Urban residents exhibited higher obesity prevalence than rural populations across nearly all wealth groups.

---

### 3. Gender Difference

Female respondents showed significantly higher odds of obesity than males, even after adjusting for wealth, age, and residence.

---

### 4. Age Effect

Obesity risk increased progressively with age, demonstrating age as an independent predictor.

---

### 5. Wealth × Residence Interaction

The influence of wealth on obesity differed significantly between urban and rural populations, particularly from the middle wealth quintile onwards.

---

### 6. Sex × Residence Interaction

The gender gap in obesity was significantly larger in urban areas than in rural settings.

---

### 7. Contextual Insight

The relationship between wealth and obesity is context-dependent rather than universal. Economic prosperity influences obesity differently depending on residential environment.

---

# 💡 Business Intelligence Insights

Instead of presenting only statistical significance, this project translates analytical findings into decision-support intelligence.

### Population Segmentation

* Wealth-based segmentation
* Urban vs Rural segmentation
* Gender-based profiling
* Age-based profiling

### High-Risk Population Identification

Identified demographic groups exhibiting the highest obesity prevalence for targeted interventions.

### Decision Support

Supports evidence-based public health planning through interactive dashboards and demographic risk profiling.

### Resource Prioritization

Enables policymakers to prioritize screening, awareness, and intervention strategies for vulnerable populations.

---

# 🚀 Innovative Contributions

* Developed a complete end-to-end analytics pipeline integrating Python, SQL, and Power BI.
* Combined statistical inference with business intelligence reporting in a single reproducible workflow.
* Applied interaction modelling to identify context-dependent obesity risk rather than relying solely on independent predictors.
* Designed population risk segmentation using wealth, residence, age, and gender for targeted public health planning.
* Created a modular and reproducible analytical pipeline suitable for large-scale survey datasets.
* Translated statistical findings into interactive decision-support dashboards for non-technical stakeholders.

---

# 📊 Dashboard Highlights

The Power BI dashboard provides:

* Executive KPI Summary
* Obesity Prevalence Overview
* Wealth-wise Risk Analysis
* Urban vs Rural Comparison
* Gender-based Comparison
* Age Group Analysis
* Population Risk Segmentation
* Interactive Filtering and Drill-down

---

# 📁 Repository Structure

```text
├── data/
├── notebooks/
├── scripts/
│   ├── metadata_extraction.py
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   ├── exploratory_analysis.py
│   ├── statistical_analysis.py
│   ├── logistic_regression.py
│   └── export_to_sql.py
│
├── sql/
│   ├── schema.sql
│   ├── analysis_queries.sql
│   └── dashboard_views.sql
│
├── powerbi/
│   └── Obesity_Analytics.pbix
│
├── dashboard_images/
│
└── README.md
```

---

# 📌 Project Outcome

This project demonstrates how statistical modelling, demographic segmentation, SQL analytics, and business intelligence can be integrated into a single analytical workflow to support evidence-based public health decision-making. By combining rigorous statistical validation with interactive dashboards, the project transforms complex survey data into actionable insights for policymakers and healthcare stakeholders.
