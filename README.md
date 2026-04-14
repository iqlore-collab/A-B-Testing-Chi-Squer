# 🧪 Clients A/B/C/D Experiment Analysis

## 🎯 Project Objective

This project analyzes an A/B/C/D experiment conducted on the Eniac homepage to evaluate which button design performs best in terms of user engagement.

The tested variants were:
- White “SHOP NOW”
- Red “SHOP NOW”
- White “SEE DEALS”
- Red “SEE DEALS”

The main goal is to determine whether design changes (color + copy) significantly affect user Click-Through Rate (CTR).

---

## 📊 Dataset Description

The dataset contains aggregated click interaction data from four homepage variants (A, B, C, D).

Each CSV file includes:

- `Element ID` – unique identifier of UI elements  
- `Tag name` – HTML tag type  
- `Name` – element label (e.g. Mac, iPhone, Accessories)  
- `No. clicks` – number of clicks per element  
- `Visible?` – visibility status of the element  
- `Snapshot information` – experiment metadata  

### Data scope:
- Total homepage visits: **50,061**
- 4 experimental variants (A, B, C, D)

---

## ⚠️ Limitations

- No user-level or session-level tracking
- No funnel or path analysis available
- Missing metrics:
  - Drop-off rate
  - Homepage-return rate

As a result, the analysis focuses on CTR and click distribution only.

---

## 🧪 Methodology

- Primary metric: Click-Through Rate (CTR)
- Statistical test: Chi-square test (χ²)
- Significance level: α = 0.05

CTR formula:
CTR = clicks / visits

---

## 📈 Key Output

- CTR comparison across all variants
- Statistical significance testing (χ²)
- Identification of best-performing variant

---

## 🚀 Business Value

This analysis supports product decisions by:
- identifying the most effective UI design,
- quantifying impact of design changes,
- enabling data-driven A/B testing decisions for homepage optimization.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SciPy

---

## 📌 Author

UX / Product Analytics Case Study – Eniac Experiment
