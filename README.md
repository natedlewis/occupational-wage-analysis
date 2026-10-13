# \# U.S. Occupational Wage Analysis

# 

# Hypothesis testing and regression on BLS Occupational Employment and Wage Statistics (OEWS) data, framed as a Glassdoor-style benchmark of platform compensation data against public labor statistics.

# 

# \*\*Tools:\*\* Python, pandas, SciPy, statsmodels, Matplotlib, Seaborn

# 

# \## Data

# BLS OEWS, state-level estimates, May 2024 (`state\_M2024\_dl.xlsx`):

# https://www.bls.gov/oes/tables.htm

# 

# \## Questions and key findings

# 1\. \*\*Highest and lowest paying states:\*\* D.C. (\&#36;109,420) is highest and Mississippi (\&#36;49,740) lowest, a gap of about \&#36;59,680.

# 2\. \*\*Weighted wage by occupation group:\*\* Management leads at about \&#36;141.5k, roughly 3.9x the lowest group (\&#36;36.0k).

# 3\. \*\*California occupation mix:\*\* California holds 11.6% of US employment and is heavily over-represented in farming, fishing and forestry.

# 4\. \*\*Management vs. production wages (F-test, Welch t-test):\*\* a significant difference of about \&#36;79k (t = 24.64, p < 0.001).

# 5\. \*\*Employment vs. wage (log-log regression):\*\* a slight negative, statistically significant slope (-0.0297, p = 0.001), but R-squared is only 0.013, so employment is a very weak predictor.

# 

# \## How to run

# pip install -r requirements.txt

# jupyter lab

# Open `occupational-wage-analysis.ipynb` and run all cells.

