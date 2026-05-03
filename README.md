# Supply Chain Delivery Analysis

## Objective
Analysed 1,80,000+ supply chain orders to identify late delivery patterns, root causes, and financial impact using Python.

## Problem Statement 
A global e-commerce company is experiencing high late delivery rates across all markets. This analysis identifies which shipping modes, markets, and product cateogries are most effected - and quantifies the financial cost of delivery failures.

## Tools and Technologies
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Git & GitHub

## Dataset
- 1,80,519 across 5 global markets
- 53 features including shipping mode, delivery status, profit, and product categories

## Key Findings
### 1. Shipping Mode Analysis
- First Class shipping has 95.32% late delivery risk
- Standard Class performs best at only 38.07% late delivery risk
- Higher priced shipping modes paradoxically perform worse

### 2. Market Analysis
- All global market show consistent ~55% late delivery rate
- Europe highest at 55.21%, LATAM lowest at 54.36%
- Problem is systematic - not religion specific

### 3. Financial Impact
- Late deliveries generate $0.78 less profit per order
- Total estimated profit loss = $77,000 across dataset
- On-time deliveries average $22.40 profit vs $21.62 for late

### 4. Category Analysis
- Golf Bags & Carts highest risk category at 68.85%
- Lacrosse (60.06%) and Pet Supplies (58.94%) follow
- 10 categories exceed 56% late delivery risk

## Business Recommendations
1. Investigate and fix First Class shipping operations immediately
2. Implement catefory-specific logistics planning for high-risk products
3. Reduce late deliveries by 10% could recover ~ $7,700 in lost profit
4. Since problem is global - focus on operational processes not regional fixes
