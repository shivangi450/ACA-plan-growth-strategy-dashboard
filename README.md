# 📊 Health Insurance Plan Attributes Analysis  
### Strategic Benchmarking Dashboard for Insurance Market Intelligence

---

## 📌 Overview

This project analyzes the **Marketplace Plan Attributes Public Use File (PUF) – PY2025** (file used in this project: **`plan_attributes_PUF.csv`**) to help health insurance companies benchmark their offerings, identify underserved markets, and optimize plan strategy. :contentReference[oaicite:0]{index=0}

Using interactive visual analytics, the dashboard translates complex plan-level data into actionable business insights for strategic decision-making.

> **Core Question:**  
> How can insurance companies use market-wide plan attribute data to improve competitiveness, retention, and geographic expansion?

---

## 🎯 Business Problem

The U.S. health insurance marketplace is competitive and saturated. Insurers face challenges such as:

- Limited visibility into competitor plan structures  
- Unclear geographic saturation levels  
- Slowing new plan growth in certain segments  
- Product misalignment with consumer preferences  
- Difficulty identifying “white-space” opportunities  

Without structured benchmarking, companies risk poor pricing decisions, reduced retention, and weaker market positioning.

---

## 💡 The Big Idea

Organizations that leverage structured health insurance data to benchmark their plans against competitors can design more competitive, compliant, and profitable offerings — while those who ignore data risk losing market share and strategic advantage.

---

# 🧾 Dataset

**Marketplace Plan Attributes Public Use File (PUF) – PY2025** (Healthcare.gov)

### Project file
- `plan_attributes_PUF.csv`

### What the dataset contains (high level)
Plan-level attributes across the ACA Marketplace, including plan design and classification fields used for market benchmarking (e.g., geography, issuer, plan type, metal level, and related plan characteristics). :contentReference[oaicite:1]{index=1}

---

# 🧩 Data Schema (Relevant to This Dashboard)

Below is the **practical schema** used for the dashboard analysis (grouped by how it supports insights).  
*(Field names can vary slightly by PUF version; the dashboard uses the columns that correspond to these concepts.)*

## 1) Geography
- **State / Location fields**: used for the interactive map (state-level distribution and saturation comparisons)
- **Rating Area / Region fields (if present)**: can support deeper drill-down beyond state

## 2) Issuer / Carrier
- **Issuer / Issuer Name / Issuer ID**: used for issuer concentration analysis and competition intensity

## 3) Plan Classification
- **Plan Type**: HMO, PPO, EPO, POS (used in treemap and breakdown comparisons)
- **Metal Level**: Bronze, Silver, Gold, Platinum, Catastrophic (used in categorical comparisons and filtering)

## 4) Plan Lifecycle / Market Movement (where applicable)
- **New vs Existing indicator**: used to compare market movement and plan growth/retention patterns

## 5) Plan Attributes (optional extensions for future versions)
- **Cost-sharing / deductible / copay / coinsurance fields**
- **Benefits / coverage fields**
These were not the primary focus of the current dashboard story but are strong candidates for future enhancements (profitability + affordability modeling).

---

# 📊 Dashboard Structure & Key Insights

The dashboard follows a storytelling flow:

1️⃣ **Geographic Market Landscape**  
2️⃣ **Plan Type Distribution**  
3️⃣ **Detailed Product & Growth Breakdown**

---

## 🗺️ 1. Geographic Distribution (Interactive Map)

Displays state-level plan concentration.

### Key Findings (examples from dashboard narrative)
- **Texas shows high concentration (4,660)**
- **Alaska shows low concentration (64)**
- Strong variation exists between high-competition vs low-competition states

### Strategic Value
- Identify primary revenue-driving states  
- Detect underserved markets for expansion  
- Allocate marketing and provider network investments strategically  
- Evaluate competitive intensity by region  

---

## 🌲 2. Plan Type Distribution (Treemap)

Shows proportional distribution of plan types across the market.

### Key Findings
- **HMO plans represent ~50% of total distribution**
- PPO and POS have lower adoption rates
- EPO holds moderate share

### Strategic Value
- Prioritize high-performing plan types  
- Reassess low-performing offerings  
- Optimize network design and pricing strategy  
- Align product portfolio with consumer behavior  

---

## 📊 3. Detailed Plan Breakdown (Horizontal Bar Chart)

Compares:
- Plan Type  
- Metal Level (Bronze, Silver, Gold, etc.)  
- New vs Existing Plans  

### Key Findings
- Existing plans represent a large share of the market (dominant vs new)
- Silver and Gold tiers show strong demand patterns
- New plan growth appears to be slower in some segments

### Strategic Value
- Improve retention strategies  
- Refine acquisition strategy  
- Innovate stagnant plan categories  
- Adjust benefit design based on demand trends  

---

# 🛠 Technical Implementation

### Tools & Technologies
- Tableau (Dashboard Development)
- Geospatial Mapping
- Treemap Visualization
- Horizontal Bar Charts
- Interactive Filters & Parameters
- Storyboarding & Data Storytelling
- Business Insight Translation
- Healthcare Market Analytics

---

# 🧠 Skills Demonstrated

This project highlights:

- Healthcare analytics domain knowledge  
- Competitive benchmarking analysis  
- Market segmentation strategy  
- Executive-level data storytelling  
- Visualization design (reducing cognitive load, clear narrative flow)  
- Interactive dashboard development  
- Business-focused insight generation  
- Strategic problem framing  

---

# 🚀 How Stakeholders Can Use This Dashboard

Insurance companies can use this dashboard to:

- Benchmark plan offerings against competitors  
- Identify underserved geographic regions  
- Optimize product mix and metal-level distribution  
- Strengthen retention strategies  
- Support data-driven expansion planning  
- Improve strategic pricing/product decisions  

---

# 📈 Business Impact Potential

If applied operationally, this framework could:

- Improve competitive positioning  
- Increase market share in underserved states  
- Optimize plan portfolio strategy  
- Reduce pricing misalignment risk  
- Enhance customer retention  
- Support regulatory benchmarking  

---

# 🔮 Future Enhancements

- Integrate multi-year trend analysis  
- Add premium/enrollment metrics (if available or joined from other sources)  
- Incorporate claims/cost data for profitability modeling  
- Apply predictive modeling for enrollment forecasting  
- Automate refresh with ETL pipelines  
- Deploy as cloud BI solution for stakeholder access  

---

# 🏁 Conclusion

This project demonstrates how structured health insurance plan data can be transformed into a strategic decision-support tool.

By combining data visualization, healthcare domain understanding, and business strategy alignment, the dashboard bridges the gap between raw plan attributes and executive-level action.
