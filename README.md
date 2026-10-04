# Soccer Prediction Model

Predicts a forward's non-penalty goals from the previous season's statistics, so a club can shortlist players before paying transfer fees. Georgetown M.S. capstone, 2022.

**Live dashboard:** https://mngoh.github.io/SPM-Model/

- Data: 2,786 players from FBref, cleaned and merged in `notebooks/0_Data_Cleaning.ipynb`
- Features: shooting, passing and possession statistics per 90 minutes, selected after the correlation analysis in `1_EDA.ipynb`
- Models: eight compared in `2_ML_Models.ipynb` (linear, regularized, tree ensembles and gradient boosting), scored on a held-out season
- Result: the dashboard shows each model's error and the top predicted scorers

Layout: `notebooks/` analysis, `data/` inputs and the merged table, `index.html` the dashboard.
