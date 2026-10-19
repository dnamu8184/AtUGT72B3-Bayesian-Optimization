# AtUGT72B3 Bayesian Optimization

This repository contains the Python notebooks used for the study:

**Bayesian Optimization of Resource-Efficient Esculetin Glycosylation Feeding Conditions by AtUGT72B3**

## Files

- `실험조건_추천.ipynb`  
  Bayesian optimization for sequential experimental condition selection using a Gaussian Process and Expected Improvement.

- `GP_예측_반응면.ipynb`  
  Visualization of GP-predicted response surfaces based on accumulated experimental data.

## Optimization variables

- Esculetin concentration: 0.10–0.50 mM
- Reaction OD600: 1.0–5.0
- Reaction time: 20–28 h

The optimization response was the **HPLC product peak area (mAU·min)**.

## Requirements

`numpy`, `pandas`, `scipy`, `matplotlib`, `scikit-optimize`
