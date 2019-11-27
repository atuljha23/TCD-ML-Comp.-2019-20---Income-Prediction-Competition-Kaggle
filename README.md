# TCD-ML-Comp.-2019-20---Income-Prediction-Competition-Kaggle
predicting the income with a more complex dataset. Competition held as a part of our course-work in Trinity College Dublin.

- **Competition Link:** https://www.kaggle.com/c/tcd-ml-comp-201920-income-pred-group/
- **Final Result: No. 1 on Public and Private Leaderboard. :trophy:**

**How I achieved such good result?**

- I asked Watson to tell me which algorithm will work the best on this dataset, and the answer was LightGBM (The most powerful and fastest training algorithm I have seen!).
- I used LightGBM with some hyperparameter tuning (with K-Fold and without K-Fold)
- After almost 54 Submission I selected the top 3 best performing model on public leaderboard and used those submission files to be used for ensembled stacked model technique.

**References**
-  Target Encoding: https://www.kaggle.com/scirpus/target-encoding
-  Stacked Ensembled Model: https://www.kaggle.com/amar09/fare-prediction-stacked-ensemble-xgboost-lgbm
