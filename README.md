**Target:** Breast cancer type 1 susceptibility protein (BRCA1)  
**Molecules:** 16 (14 inactive, 2 active)

## Project Structure
- `notebooks/` → Jupyter notebooks for EDA, fingerprints, etc.
- `data/` → Raw & processed CSV files (Lipinski descriptors, PubChem fingerprints)
- `figures/` → All generated plots (boxplots, scatter, bar, histogram)
- `reports/` → Final summary report 

## Key Insights
- LogP shows the strongest difference between active and inactive compounds.
- pIC50 is the only statistically significant feature (Mann-Whitney p < 0.05).
- PubChem fingerprints: 881 bits.
