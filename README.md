# Explorando-Factores-de-Comportamiento-en-NovaRetail

# 📊 NovaRetail+ | Customer Behavior Analysis 

## Problem Solved 

This project analyzes customer behavior data from NovaRetail+ to identify which factors are most strongly associated with annual customer revenue. 

Using exploratory data analysis (EDA) and multiple correlation techniques, the project identifies behavioral patterns that can support business decisions related to marketing, customer retention, and revenue growth. 
---
## Project Structure 

The notebook is organized into the following sections: 

1. Data loading and initial exploration.
2. Data preparation and validation.
3. Exploratory visualizations.
4. Correlation analysis:
   - Pearson
   - Spearman
   - Point-biserial
   - Cramér's V
5. Business insights and interpretation.
6. Limitations and future work.

---
8. ## Technologies sed

   - Python
   - Pandas
   - NumPy
   - Matplotlib
   - Seaborn
   - SciPy
   - Jupyter Notebook
   
   ---

   ## How to Reproduce the Analysis

   1. Clone this repository.
   2. Install the required libraries:

   ```
   bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
   3. Place the dataset:
   ```
   6. /datasets/novaretail_comportamiento_clientes_2024.csv
    ```
   Open the notebook:
  ```
S8 Student Version-Project-NovaRetail.ipynb
```
5. Run the notebook from top to bottom.
---
9. ## Key Findings
  - Customer purchases per month showed the strongest positive relationship with annual revenue.
  - Monthly visits presented a moderate positive association.
  - Advertising spend showed a weak positive relationship.
  - Premium membership and customer churn exhibited relatively weak associations with annual revenue.
---
  ## Future Improvements 
- Build predictive models for annual revenue.
- Incorporate additional customer segmentation.
- Explore causal relationships beyond correlation analysis.
