# Tea Beverage Store Expansion Analysis (China) 2025.6.1

This project analyzes **store expansion patterns and regional market potential** in China’s new-style tea beverage industry, using store-level and regional data.
The focus is on understanding **where brands expand, why regional differences emerge, and where future store growth may be constrained or underexploited**, with a detailed case study on **Mixue Ice Cream**.

---
## Project Highlights
- Compare store scale, pricing tiers, and expansion speed across major brands
- Identify **seasonal patterns** in store openings
- Analyze **regional market structure** by city tier and province
- Model store distribution using regression and clustering
- Estimate **store expansion potential** at the provincial level
---
## Files
- `MilkTea analysis.Rmd`  
  Reproducible R Markdown file containing the full analysis pipeline:
  - data processing  
  - visualization  
  - statistical tests  
  - econometric models  
---
## Methods Used
- Exploratory data analysis (EDA)
- Non-parametric tests (seasonality analysis)
- Log-log regression models
- Count models (Poisson / Negative Binomial)
- K-means clustering

---
## Data
- Store distribution and brand data from public industry platforms
- Provincial population and income statistics
- City-tier classifications
Data are aggregated at the **province** and **city-tier** levels.

---
## Key Insights
- Population size and regional climate explain most cross-province differences in store density  
- Income affects **brand positioning**, not total store count  
- Mixue Ice Cream shows strong penetration in lower-tier markets but uneven saturation across provinces  
- Several populous provinces remain **under-penetrated** relative to model-implied capacity
---
## Notes
This project is intended as a **personal data analysis portfolio piece**.  
Results depend on data availability and modeling assumptions and are not investment or business advice.
