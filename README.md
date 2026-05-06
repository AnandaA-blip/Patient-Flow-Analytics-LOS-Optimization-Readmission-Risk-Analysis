<div align="center">

# 🏥 Hospital Patient Flow Analysis

### *From Admission to Readmission — Uncovering Hidden Patterns in Hospital Data*

[![Notebook](https://img.shields.io/badge/Open_Notebook-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/drive/1XUO50q1ixCFh0Tf9tmzJ_jrYuOEYEHyr?usp=sharing)
[![Dashboard](https://img.shields.io/badge/Live_Dashboard-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://datastudio.google.com/reporting/d429c6fb-be3b-461d-bf35-f92af18e4eea)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ananda-anugrah-062741387/)


</div>

---

## 🔎 Overview

> Analyzing **3,000 patient encounters** across 5 hospital departments to identify readmission risk patterns, LOS bottlenecks, and operational inefficiencies — enabling evidence-based decisions for hospital management.

**Tools used:**
`Python` · `SQL` · `Pandas` · `Seaborn` · `Google Sheets` · `Looker Studio`

---

## 🔍 Key Findings

| # | Finding | Value | Benchmark | Status |
|---|---------|-------|-----------|--------|
| 1 | 30-Day Readmission Rate | **23.5%** | ≤15% (JCI) | 🔴 +57% above standard |
| 2 | Prolonged Stay Rate (LOS ≥6d) | **17.6%** | ≤15% | 🟡 Above target |
| 3 | Readmission — Chronic patients (all ages) | **35.2–40.8%** | — | 🔴 Critical |
| 4 | Avg Wait Time — Scheduled patients | **~44.3 min** | ≤30 min | 🔴 +47% longer |
| 5 | Wait Time Gap (Scheduled vs Emergency) | **+18–20 min** | — | 🔴 Systemic issue |

### 💡 Top Insights

**1. Chronic condition is the strongest readmission predictor**
Chronic patients aged 35–49 have the highest readmission rate (**40.8%**), surpassing even seniors 65+ (38.1%). The gap between Chronic and Non-Chronic patients is consistently **~23–27 percentage points** across all age groups — making chronic condition a far stronger predictor than age alone.

**2. Prolonged Stay is a triple burden**
Patients with LOS ≥6 days incur **2.5× higher costs**, a **30.2% readmission rate** (vs 18.0% for short stays), and the lowest satisfaction scores — all simultaneously. Discharge planning intervention on this segment delivers the highest return on investment.

**3. Oncology has the largest High vs Low-Risk readmission gap**
Despite not having the highest absolute readmission rate, Oncology shows the widest gap between High-Risk and Low-Risk patients (**10.3 percentage points**) — indicating that risk profiling is the most decisive factor in this department.

**4. Scheduled patient wait time is a systemic bottleneck**
Elective patients wait **18–20 minutes longer** than emergency patients across all 5 departments — a counterintuitive finding that points to a systemic scheduling process failure, not a single-department issue.

---

## ✅ Recommendations

| Priority | Recommendation | Target Impact |
|---|---|---|
| 🔴 High | **R1: Chronic Care Bridge** — 7-day post-discharge follow-up for all chronic patients | Reduce chronic readmission from ~39% to ≤25% |
| 🔴 High | **R2: Proactive Discharge Planning** — Case Manager review triggered at LOS Day 4 | Reduce Prolonged Stay from 17.6% to ≤12% |
| 🔴 High | **R3: Oncology Post-Discharge Program** — Dedicated care coordinator for High-Risk patients | Close HR vs LR gap from 10.3 to ≤6 points |
| 🟡 Medium | **R4: Elective Scheduling Redesign** — H-1 confirmation system for scheduled patients | Reduce scheduled wait time from ~44 to ≤30 min |
| 🟡 Medium | **R5: Real-Time KPI Dashboard** — Daily monitoring with threshold alerts | Enable proactive hospital management |

---

## 📊 Dashboard Preview

> 🔗 [**View Interactive Dashboard →**](https://datastudio.google.com/reporting/d429c6fb-be3b-461d-bf35-f92af18e4eea)

| Page 1 — Patient Flow Overview | Page 2 — Risk & Bottleneck |
|---|---|
| ![Page 1](dashboard/page1-preview.png) | ![Page 2](dashboard/page2-preview.png) |

---

## ⚠️ Disclaimer

Dataset is synthetic ([Kaggle — Healthcare Patient Journey](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)) and intended for portfolio demonstration only.

---

<div align="center">

**Author : Ananda Anugrah**

[![Email](https://img.shields.io/badge/anandaanugrah901@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:anandaanugrah901@gmail.com)

*"Built with curiosity, structured with data, communicated with clarity."*

</div>
