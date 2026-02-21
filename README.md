# Spectrum Shades LLC – Concrete Pigment Quality Analysis

## Project Overview

Spectrum Shades LLC is experiencing increasing customer complaints related to inconsistent concrete pigment color quality.  
This project analyzes production data to identify potential operational and material factors contributing to quality variability.

The goal is to provide data-driven insights to improve product reliability and reduce customer dissatisfaction.

---

## Business Problem

Inconsistent pigment color quality has resulted in:
- Increased customer complaints
- Higher return rates
- Reduced customer trust

Understanding the statistical and operational drivers behind quality variation is critical for process improvement.

---

## Objectives

- Clean and validate production data
- Identify supplier-level differences
- Analyze pigment quantity impact on quality
- Calculate variability using standard deviation
- Measure correlation between pigment quantity and product quality

---

## Dataset

The dataset contains production-level information including:

- `batch_id`
- `production_date`
- `raw_material_supplier`
- `pigment_type`
- `pigment_quantity`
- `mixing_time`
- `mixing_speed`
- `product_quality_score`

*Dataset not included due to confidentiality.*

---

## Analysis Performed

### 1. Data Cleaning
- Handled missing values
- Validated pigment quantity ranges
- Standardized categorical values
- Converted date formats

### 2. Supplier-Level Aggregation
- Calculated average product quality score per supplier
- Calculated average pigment quantity per supplier

### 3. Conditional Filtering
- Analyzed subsets of data based on supplier and pigment thresholds

### 4. Statistical Analysis
- Mean calculation
- Standard deviation measurement
- Pearson correlation analysis

---

## Key Findings

- Differences were observed between suppliers in terms of average quality scores.
- Pigment quantity shows measurable correlation with product quality.
- Variability in product quality suggests process stabilization opportunities.

---

## Business Insights

The analysis indicates that:
- Supplier selection may impact final product quality.
- Pigment quantity plays a role in quality outcomes.
- Process variability should be further controlled and monitored.

Data-driven monitoring systems are recommended to reduce inconsistency.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Statistical Analysis
- Correlation Analysis

---

## Project Structure
│
├── analysis.ipynb
├── README.md
└── (dataset not included)


---

## Author

Orkhan Zeynalli  
Data Analyst | Business & Statistical Analysis
