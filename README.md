# Analysis of Health Insurance Plan Attributes (Tableau Dashboard)

A Tableau dashboard + storyboard that helps **health insurance companies** identify growth opportunities by visualizing:
- **State-wise concentration** of plan counts (market saturation vs underserved states)
- **Plan type dominance** (HMO/EPO/PPO/POS)
- **Metal level distribution** and the split between **new vs existing** plan counts


---

## Problem this project solves
Health insurance markets are competitive and saturated. Companies often compete in the same large states with similar plan offerings.  
This project highlights **where plan availability is crowded** and where there may be **white-space opportunities** to introduce differentiated plans (e.g., PPO options, HSA-eligible plans) based on regional patterns.

---

## Dataset
- **Plan Attributes PUF (PY2025)** from healthcare.gov (ACA Marketplace plan attributes).  
File used: `data/raw/plan_attributes_PUF.csv`

---

## Tools
- Tableau (Dashboard, filters, parameters, storyboard)
- Supporting write-ups in `/docs/assignments`

---

## Key insights (example takeaways)
These insights are taken directly from the project storyboard and dashboard interpretation:
- **Geographic concentration:** Texas shows the highest plan count (4,660) while Alaska is much lower (64) → indicates saturation vs under-penetration.
- **Plan preference:** HMO is the dominant plan type (about ~50% in the treemap), suggesting consumers prefer structured networks.
- **New vs existing:** Existing plans represent the majority (~75%), with strong concentration in HMO + Gold categories—suggesting retention is strong but **new growth may require plan innovation**.

---

## Repository structure
```
health-insurance-plan-attributes-dashboard/
├─ README.md
├─ PROJECT_OUTCOME_IMPACT.txt
├─ CITATION.md
├─ LICENSE
├─ data/
│  └─ raw/
│     └─ plan_attributes_PUF.csv
├─ tableau/
│  ├─ workbooks/
│  │  ├─ Module_06_Workbook.twbx
│  │  ├─ Module_10_Workbook.twbx
│  │  └─ Module_11_Final_Dashboard.twbx
│  └─ exports/                  # optional (images/PDF exports if you add later)
├─ docs/
│  └─ assignments/              # storyboard + written reflections
└─ assets/
   ├─ images/                   # add dashboard screenshots here
   └─ video/                    # add demo video or link in README
```

---

## How to view the dashboard
### Option A — Tableau Desktop
1. Download any `.twbx` file from `tableau/workbooks/`
2. Open in Tableau Desktop

### Option B — Free Tableau Reader
1. Install Tableau Reader
2. Open `tableau/workbooks/Module_11_Final_Dashboard.twbx`

---

## What to add next (recommended)
- Add 1–3 dashboard screenshots to `assets/images/` and embed them in this README
- Export the final dashboard as PDF/PNG into `tableau/exports/`
- Add a short demo video link (YouTube) under a “Demo” section

---

## Acknowledgements
- Dataset: healthcare.gov Plan Attributes PUF (PY2025)
- Course: UNT ADTA 5250 – Large Data Visualization
