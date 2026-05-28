# Student-Performance-Analyzer

## Overview
An exploratory data analysis of 395 Portuguese high school students 
to identify what factors most affect final academic performance.

## Dataset
- Source: UCI Machine Learning Repository via Kaggle
- 395 students, 33 features
- Key target variable: G3 (final grade out of 20)

  ## Key Findings
1. **Past failures are the strongest negative predictor** — students 
   With 3 prior failures, the score has a median of 8 vs 12 for students 
   with none
2. **Family education matters more than study time** — mother's 
   education (Medu) correlates 0.19 with the final grade vs 
   studytime at 0.13
3. **Early grades predict everything** — G1 and G2 correlate 
   0.89–0.97 with G3. Students struggling in period 1 are almost 
   always struggle in period 3
4. **9.6% of students never made it to the final exam** — 38 out 
   of 395 scored 0, removed from main analysis as likely dropouts

   ## Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab

## Visualizations
- Grade distribution histogram
- Study time vs final grade boxplot
- Past failures vs final grade boxplot
- Absences vs final grade scatterplot
- Correlation heatmap across all numerical variables

## How to Run
1. Open the notebook in Google Colab
2. Run all cells in order
3. Dataset downloads automatically via kagglehub
