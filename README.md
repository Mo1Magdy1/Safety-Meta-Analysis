# 🧪 Safety profile of glucokinase activator AZD1656: systematic review and meta-analysis of 23 randomised trials in diabetic and healthy volunteers with relevance to immunomodulatory therapy

<img width="90%" height="600" alt="image" src="https://github.com/user-attachments/assets/1b480205-2791-478e-8640-255cb3d13b41" />

---

## 📄 Project Overview
This repository contains the R code and analysis files for a **systematic review and meta-analysis** of 23 randomized controlled trials evaluating the **safety profile of AZD1656**, a glucokinase activator (GKA) with both **anti-diabetic** and **immunomodulatory** potential.

The study followed **PRISMA guidelines**, with data extracted from eligible trials and analyzed in R.

---

## 🏆 Publication
> 📚 **Published in**: *Inflammopharmacology* (Springer Nature)  
> 🏅 **Journal Rank**: Q1 in Pharmacology  
> 📈 **Impact Factor (2024)**: 5.3  
> 🔗 [View Publication](https://doi.org/10.1007/s10787-025-01785-z)

---

## 📊 Methods & Analysis
- **Data Extraction** for:
  - Total non-serious adverse events  
  - Hypoglycaemic adverse events  
  - Serious adverse events  
  - Stratification across **low (<100 mg)**, **medium (100–200 mg)**, and **high (>200 mg)** dose ranges  
- **Statistical Analysis**:
  - Fixed-effect meta-analysis using **Relative Risk (RR)**
  - Continuity correction for zero-event studies
  - Forest plots for pooled effect estimates
  - Funnel plots & **Egger’s test** for publication bias
- **All analyses performed in R** using `meta`, `metafor`, and `dmetar` packages

---
