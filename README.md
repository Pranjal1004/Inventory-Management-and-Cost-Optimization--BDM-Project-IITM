# Inventory Management & Cost Optimization
### Business Data Management Capstone Project | IIT Madras DS Diploma

A data-driven inventory management and purchase optimization system developed for **Rajesh Surgical**, a wholesale medical supplies business. This project leverages Python and Microsoft Excel to analyze three years of purchasing data, classify inventory, forecast demand, and identify procurement cost-saving opportunities.

---

## Project Overview

Traditional inventory decisions at Rajesh Surgical were based largely on experience rather than analytical insights. This project transforms historical purchase records into actionable business intelligence by:

- Cleaning and preprocessing three years of raw purchase data
- Performing inventory prioritization using ABC-VED Analysis
- Forecasting future demand for critical products
- Identifying seasonal purchasing patterns
- Detecting supplier price fluctuations
- Recommending optimal purchasing periods
- Providing inventory and procurement recommendations

---

## Business Problem

The project addresses two major business challenges:

### 1. Inventory Planning

- Overstocking of slow-moving products
- Understocking of high-demand products
- Lack of demand forecasting
- Inefficient inventory prioritization

### 2. Cost Optimization

- Supplier price fluctuations
- Non-optimized purchasing decisions
- Missed opportunities for bulk procurement
- Higher procurement costs

---

## Dataset

- **Industry:** Medical & Surgical Supplies
- **Business:** Rajesh Surgical
- **Duration:** April 2022 – March 2025
- **Records:** 28,000+ purchase transactions
- **Unique Products:** 1,700+

Main attributes include:

- Date
- Product Name
- Quantity
- Rate
- Amount

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Microsoft Excel
- Jupyter Notebook

---

## Project Workflow

```
Raw Purchase Data
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
ABC Analysis
        │
        ▼
VED Classification
        │
        ▼
Demand Pattern Classification
        │
        ▼
Forecasting
(Holt-Winters / Croston)
        │
        ▼
Price Variability Analysis
        │
        ▼
Business Recommendations
```

---

## Analysis Performed

### Data Cleaning

- Merged three years of purchase records
- Standardized product names
- Removed duplicate entries
- Corrected formatting inconsistencies
- Validated purchase amounts

---

### Exploratory Data Analysis

- Purchase trends
- Product demand distribution
- Outlier detection
- Seasonal analysis
- Price analysis

---

### ABC Analysis

Inventory classified based on annual purchase value:

- **A:** High-value products
- **B:** Medium-value products
- **C:** Low-value products

---

### VED Analysis

Critical products categorized as:

- **Vital**
- **Essential**
- **Desirable**

---

### Demand Classification

Products classified into:

- Regular demand
- Intermittent demand

using

- Coefficient of Variation (CV)
- Zero-demand Months

---

### Forecasting Models

#### Holt-Winters Exponential Smoothing

Used for products with regular demand patterns.

#### Croston's Method

Used for intermittent-demand products with sparse purchase history.

---

### Price Variability Analysis

Identified:

- Price volatility
- Best purchasing months
- Bulk purchasing opportunities
- Procurement savings

---

## Key Results

✔ Prioritized inventory using ABC-VED Matrix

✔ Forecasted demand for critical products

✔ Identified seasonal purchasing behavior

✔ Recommended procurement schedules

✔ Identified products with high price volatility

✔ Estimated **15–30% procurement cost savings** for selected products

---

## Repository Structure

```
├── Analysis/
├── Proof of Originality/
├── Raw Data/
├── descryptive stats.xlsx
├── Final Report
├── Mid term report
├── Proposal
├── PPT
└── README.md
```

*(Update this section according to your actual folder structure.)*

---

## Future Improvements

- Inventory Dashboard (Power BI)
- Streamlit Web Application
- EOQ Model
- Safety Stock Optimization
- Reorder Point Prediction
- Supplier Performance Analysis

---

## Business Impact

This project demonstrates how data analytics can improve procurement decisions, reduce inventory costs, optimize stock levels, and support evidence-based inventory planning in the healthcare supply chain.

---

## Author

**Pranjal Dubey**

- IIT Madras Diploma in Data Science
- M.Sc. Operational Research, University of Delhi

---

## License

This project is intended for educational and portfolio purposes.
