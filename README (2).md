# BCSE331L Exploratory Data Analysis — Course Project

**Dataset:** S&P 500 Constituents
`https://raw.githubusercontent.com/salemprakash/EDA/main/Data/constituents.csv`

All three phases are in a single notebook: `Phase1_EDA_constituents.ipynb`

## Phase I
Loading, basic statistics, missing data, cleaning, transformation, and univariate / bivariate / multivariate analysis (4 visualizations each).

## Phase II
1D, 2D and 3D statistical analysis, K-Means clustering (elbow + silhouette) and Hierarchical clustering (Ward dendrogram, linkage comparison).

## Phase III
- Module 6: Principal Component Analysis (scree plot, loadings, biplot)
- Module 7: Simple Linear Regression (founding year vs year added to the index, with diagnostics)

## Notes
The raw data is mostly categorical, so numeric features (`Founded_Year_Clean`, `Company_Age`, `Date_Added_Year`, `Years_In_Index`, `Founded_Era`) are engineered in the cleaning and transformation steps. Only three variables are genuinely numeric (founding year, year added, CIK), so the clustering and regression results describe timing patterns, not company performance.
