# EDA Course Project — Phase 1

**Dataset:** S&P 500 Constituents
`https://raw.githubusercontent.com/salemprakash/EDA/main/Data/constituents.csv`

## Contents
- `Phase1_EDA_constituents.ipynb` — Phase 1 notebook (5 marks), covering:
  1. Loading the dataset
  2. Basic statistical analysis
  3. Handling missing data
  4. Data cleaning
  5. Data transformation
  6. Univariate analysis (4 visualizations)
  7. Bivariate analysis (4 visualizations)
  8. Multivariate analysis (4 visualizations)

## How to run
1. Open the notebook in Google Colab (`File > Open notebook > GitHub`, paste this repo's URL).
2. Run all cells top to bottom (`Runtime > Run all`). The dataset is loaded directly
   from the raw GitHub URL above, so no manual upload is needed.
3. After running, save a copy back to this same repository
   (`File > Save a copy in GitHub`) so the executed outputs are committed.

## Notes
The raw dataset is almost entirely categorical (ticker symbol, company name, GICS
sector/sub-industry, headquarters location, date added, CIK, founding year — the
last of which sometimes contains extra text such as `"2020 (1915, spinoff)"`).
The **Data Cleaning** and **Data Transformation** sections parse and engineer
numeric features (`Founded_Year_Clean`, `Company_Age`, `Date_Added_Year`,
`Years_In_Index`, `Founded_Era`, and a split `HQ_City` / `HQ_State_Country`) so
that statistical summaries, correlations, and distribution plots are meaningful.

Phases 2 and 3 of the project will build on this same cleaned dataset and repository.
