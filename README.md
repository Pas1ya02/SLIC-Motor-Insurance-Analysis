# SLIC Motor Insurance Claims Analysis & Risk Modelling 

**Project**: Motor Insurance Claims Analysis & Risk Modelling for Sri Lanka Insurance Corporation (SLIC) — simulated microdata calibrated to SLIC 2024 Annual Report metrics. 
**Author**: Pasindu Perera 

## Overview This repository contains a reproducible end-to-end analysis: data simulation, EDA, actuarial modelling (frequency & severity), pure premium calculation, pricing recommendations, and reserving (IBNR) using Chain-Ladder methods.

## Key Deliverables 
- notebooks/SLIC_Motor_Insurance_Analysis.ipynb
- Jupyter notebook with code, commentary, and figures - reports/SLIC_Analysis_Report.pdf
- Polished PDF report summarising methods, findings and recommendations - slides/SLIC_Analysis_Slides.pdf
- 5-slide presentation for recruiters - data/simulated_motor_portfolio.csv — Simulated policy and claim dataset (CSV) - src/ — Supporting scripts to reproduce simulation, models, and results 

## Project Goals 
1. Create a realistic simulated motor portfolio calibrated to SLIC's reported GWP and claim figures.
2. Build GLM-based frequency and severity models (Negative Binomial / Gamma).
3. Compute pure premiums and technical premiums using SLIC expense ratios.
4. Estimate IBNR using Chain-Ladder and provide reserving guidance.
5. Produce report and slides suitable for hiring managers and actuarial recruiters.
  
## How to run 
1. Create and activate a Python virtual environment :

bash
python -m venv venv

source venv/bin/activate # Linux / macOS

venv\Scripts\activate # Windows PowerShell  
