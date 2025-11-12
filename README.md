# Kimia Farma Business Performance Analysis (2020-2023)

> Project-Based Virtual Internship: Big Data Analyst  
> **Kimia Farma × Rakamin Academy**

## About the Project

This project analyzes Kimia Farma's business performance from 2020 to 2023 using BigQuery for data processing and Looker Studio for visualization. Kimia Farma, established in 1817, is Indonesia's first pharmaceutical company, now operating as an integrated healthcare provider. The analysis consolidates 650,000+ transactions from four operational datasets to provide actionable insights for strategic decision-making.

## Problem Statement

Kimia Farma needs an integrated analysis of its business performance across 2020–2023. Dispersed data across multiple sources makes it challenging to:
- Track sales trends and profit margins
- Identify high-performing products and branches
- Understand customer satisfaction patterns
- Make data-driven strategic decisions

## Objectives

1. Consolidate four datasets into a unified analytical table
2. Create interactive performance dashboards
3. Derive actionable insights for business strategy
4. Identify growth opportunities and operational inefficiencies

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **Google BigQuery** | Data warehousing & SQL processing |
| **Looker Studio** | Interactive dashboards & reporting |
| **Google Cloud Platform** | Cloud infrastructure |
| **GitHub** | Version control & documentation |

## Data Sources

The analysis uses four main datasets:

1. **kf_final_transaction.csv** - Transaction records (650K+ rows)
2. **kf_product.csv** - Product catalog and pricing
3. **kf_inventory.csv** - Stock management data
4. **kf_kantor_cabang.csv** - Branch information and ratings

## Methodology

### 1. Data Integration
- Merged four datasets using LEFT JOIN operations
- Maintained 100% data integrity (zero record loss)
- Enriched transactions with branch and product details

### 2. Business Logic Implementation

**Gross Profit Percentage** (based on price tiers):
- Price ≤ Rp 50,000 → 10% margin
- Rp 50,001 - 100,000 → 15% margin
- Rp 100,001 - 300,000 → 20% margin
- Rp 300,001 - 500,000 → 25% margin
- Price > Rp 500,000 → 30% margin

### 3. Dashboard Development
Created three-tier dashboard architecture:
- **Strategic Executive Dashboard** - C-level KPIs
- **Branch Performance Dashboard** - Operational metrics
- **Comprehensive Analytics Dashboard** - Deep-dive analysis

## Key Findings

### 1. **Zero Growth Challenge**
- 0% YoY growth (2020-2023) vs competitor's 7%
- Flat performance across all products, branches, and regions
- Predictable seasonal cycles without real growth

### 2. **Discount Strategy Failure**
- Discounts reduce profit by 14.8% (0% to 15% discount range)
- Customer ratings remain constant at 4.0 regardless of discounts
- Zero correlation between discounts and customer satisfaction

### 3. **Broken Rating System**
- All branches score **4.45** uniformly
- Transaction ratings show minimal variance (3.9-4.09)
- Ratings don't correlate with sales or operational performance

### 4. **Mid-Tier City Success**
- Mid-tier cities outperform metropolitan areas
- Consistent 28-30% profit margins
- Top products: Psycholeptics category

### 5. **Pharmacy-Only Model Wins**
- Pharmacy-only format shows highest efficiency
- IDR 186.8M average sales vs. integrated models
- Clinic and lab additions show minimal ROI impact

### 6. **Customer Segmentation Insights**
- Champions & Loyal customers: 40% of revenue (Rp 215.2T)
- At-risk segments hold Rp 61.2T requiring intervention
- 264,000+ customers analyzed across 11 segments

## Dashboards

### 1. Strategic Executive Dashboard
**Purpose**: C-level performance overview  
**Key Metrics**: Total Revenue, Profit, Gross Margin, Average Rating  
**Features**:
- Monthly sales & profit trends
- Geographic performance analysis
- Top products ranking
- Branch type comparison
- Category profitability

### 2. Branch Performance Dashboard
**Purpose**: Operational monitoring for regional managers  
**Key Metrics**: Branch rating, MoM growth, transaction count  
**Features**:
- Daily sales trends
- Product performance by branch
- Customer feedback analysis
- Discount vs. profitability scatter
- Day-of-week patterns

### 3. Comprehensive Analytics Dashboard
**Purpose**: Multi-dimensional exploratory analysis  
**Features**:
- Anomaly detection
- Customer lifetime value analysis
- Product performance matrix
- Branch efficiency quadrant
- Geographic heatmap

🔗 **[View Live Dashboards](https://lookerstudio.google.com/s/kZyfhjjKGOQ)**

## Key Learnings

- Data integration and ETL processes at scale
- Business intelligence dashboard design
- SQL optimization for large datasets
- Customer segmentation and RFM analysis
- Strategic data storytelling

## Contact

**Az-Zukhrufu Fi Silmi Suwondo**

- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/az-zukhrufu-fi-silmi-suwondo/)
- Email: afsilmis@gmail.com
- GitHub: [@yourusername](https://github.com/afsilmis)
- Dashboard: [View Live Dashboard](https://lookerstudio.google.com/s/kZyfhjjKGOQ)

---

## License

This project is part of Rakamin Academy's Project-Based Internship program.

⭐ **If you found this project helpful, please give it a star!**

**#PastiBerImpact** | **#ProjectBasedInternship** | **#RakaminAcademy**
