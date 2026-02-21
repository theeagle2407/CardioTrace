# CardioTrace
### Mapping the Future of Cardiovascular Risk

**Hackathon:** Byte 2 Beat - Hack4Health 2026  
**Author:** Elijah Oreoluwa  
**Live App:** https://huggingface.co/spaces/Elijahoreoluwa1/CardioTrace

---

## Overview
CardioTrace is a cardiovascular risk trajectory forecasting system that goes 
beyond binary prediction. It simulates how a patient's cardiovascular risk 
evolves over time and provides clinician-friendly explanations using SHAP.

## Key Results
- Test AUC: 0.963
- 5-Fold CV AUC: 0.870 +/- 0.028
- Model: LightGBM
- Dataset: UCI Cleveland Heart Disease (303 patients)

## Features
- Account-based clinical dashboard with login
- 13-parameter patient risk assessment
- Simulated 5-step risk trajectory chart
- Per-patient SHAP feature explanation
- Downloadable PDF risk report per patient

## How to Run
1. Open the Kaggle notebook and run all cells
2. Or visit the live app directly: https://huggingface.co/spaces/Elijahoreoluwa1/CardioTrace

## Requirements
See requirements.txt

## References
- Detrano et al. (1989). American Journal of Cardiology.
- Lundberg & Lee (2017). NeurIPS.
- Ke et al. (2017). LightGBM. NeurIPS.
- WHO (2024). Cardiovascular diseases fact sheet.
