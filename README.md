# MUELLER Brand Competitive Analysis in the Pasta Category

This project analyzes the performance of the MUELLER brand within the pasta category using transaction-level retail data.  
The analysis combines SQL data extraction, Python-based analytics, and the Dirichlet model to evaluate brand performance and competitive positioning.

The goal is to understand MUELLER’s market share, customer behavior, and growth opportunities compared to competing brands.

---

# Project Overview

Retail brands operate in highly competitive environments where understanding customer behavior and market dynamics is essential.

This project conducts a **data-driven competitive analysis** using the Dunnhumby dataset, focusing on:

- brand performance
- customer behavior
- category demand trends
- competitive benchmarking

The project also applies the **Dirichlet model** to validate observed patterns and provide theoretical benchmarks for comparison.

---

# Business Problem

MUELLER is a pasta brand competing with major players such as Private Label, Ragu, and Prego.

Key challenges include:

- relatively low market share
- declining household penetration
- unstable sales performance over time

The project aims to answer:

- How does MUELLER perform compared to competitors?
- Is the brand losing or retaining customers?
- What drives category demand?
- What strategies can improve MUELLER’s growth?

---

# Dataset

The analysis uses the **Dunnhumby Carboload dataset**, which includes:

- transaction-level sales data
- product information
- household purchase behavior

Key tables:

- `dh_transactions`
- `dh_product_lookup`
- `dh_causal_lookup`

Data was extracted using SQL and processed in Python. :contentReference[oaicite:0]{index=0}

---

# Tools & Technologies

- **SQL** — data extraction and joins
- **Python (Pandas, NumPy)** — data cleaning and transformation
- **Matplotlib / Seaborn** — visualization
- **Dirichlet Model** — benchmarking brand performance

---

# Methodology

The project follows a structured analytics workflow:

---

## 1. Data Preparation

- Joined transaction and product tables using SQL
- Exported cleaned dataset to CSV
- Removed duplicates and invalid records
- Handled time variables and ensured consistent time periods :contentReference[oaicite:1]{index=1}

---

## 2. Exploratory Data Analysis (EDA)

Built customer dashboards to analyze:

### Focal Brand (MUELLER)

- total revenue
- total households
- total baskets
- purchase frequency

Findings:

- Market share: **~9.5%**
- Purchase frequency: **~2.06**
- Sales show a declining trend over time :contentReference[oaicite:2]{index=2}

---

### Competitive Analysis

Compared MUELLER with top competitors:

- Private Label (~20% market share)
- Ragu
- Prego

Insights:

- MUELLER has lower market share but **higher purchase frequency**
- Indicates **strong customer loyalty but limited reach** :contentReference[oaicite:3]{index=3}

---

### Category Demand Analysis

Analyzed overall pasta category trends:

- strong demand overall
- clear seasonal fluctuations
- demand peaks in specific quarters (e.g., Quarter 6) :contentReference[oaicite:4]{index=4}

---

## 3. Dirichlet Model Analysis

Applied the Dirichlet model to validate brand performance.

### Model Validation

- predicted penetration and purchase frequency closely match actual data
- confirms realistic market behavior :contentReference[oaicite:5]{index=5}

---

### Key Findings

- MUELLER penetration: ~12% (lower than competitors)
- Repeat purchase rate: **~51% (very high)**
- Strong loyalty but insufficient market reach :contentReference[oaicite:6]{index=6}

---

### Model Accuracy

- MAPE < 10%
- Good model fit and reliability :contentReference[oaicite:7]{index=7}

---

# Key Insights

- MUELLER has **strong customer loyalty but low penetration**
- Sales fluctuations indicate unstable performance
- Competitors dominate through wider reach
- Category demand is seasonal and promotion-driven

---

# Business Recommendations

- **Increase penetration**  
  Expand customer base through targeted marketing campaigns

- **Leverage loyalty**  
  Use loyalty programs to increase repeat purchases

- **Improve brand positioning**  
  Differentiate from Private Label through quality or branding

These recommendations are supported by both empirical analysis and Dirichlet model insights. :contentReference[oaicite:8]{index=8}

---

# Why This Project Matters

This project demonstrates:

- end-to-end data analysis workflow
- ability to connect data with business decisions
- advanced analytical modeling (Dirichlet)
- strong storytelling and insight generation

