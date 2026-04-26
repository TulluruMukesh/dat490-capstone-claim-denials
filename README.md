# DAT 490 Capstone — Healthcare Insurance Claim Denial Patterns

**Team:** Nathaniel Huffman | Naga Sathvik Kommareddy | Mukesh Tulluru  
**Arizona State University — W. P. Carey School of Business | April 2026**

---

## Notebooks

| File | Description |
|------|-------------|
| `EDA.ipynb` | Data acquisition, FIPS standardization, dataset merging, and all EDA plots across RQ1 (MLR ratios), RQ2 (SVI/uninsured), and RQ3 (DE-SynPUF claims) |
| `Methodology.ipynb` | Statistical models (GLM quasi-beta, mixed-effects HLM), ML models (Random Forest, XGBoost, Neural Net, Ensemble), SHAP analysis, and fairness audit |

---

## Research Questions
1. Did AI-assisted claims processing reduce Medical Loss Ratios after 2021?
2. Do socially vulnerable counties face higher uninsured rates (double disadvantage)?
3. Can ML models predict Medicare claim denials fairly across racial groups?

---

## Data Sources
Raw data files are not included due to file size. All datasets are freely 
available from official federal portals — see Section 3.1 of the final report.

- CMS Medical Loss Ratio Data (2018–2024)
- CDC Social Vulnerability Index (2022)
- CDC PLACES County Health Data (2025)
- HRSA Area Health Resources Files (2023–2024)
- HUD ZIP-County Crosswalk (Q4 2024)
- CMS DE-SynPUF Medicare Claims (2008–2010)
- CFPB Consumer Complaint Database
