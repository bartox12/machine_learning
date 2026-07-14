# Lab 01 — Gradient boosting & stacking

Ensemble methods for regression, built up from first principles and then compared with production libraries:

- **Gradient boosting from scratch** — a depth-1 decision-stump regressor as the weak learner, boosted sequentially, and benchmarked against scikit-learn's `GradientBoostingRegressor`.
- **XGBoost vs LightGBM vs CatBoost** head-to-head on the Ames House Prices dataset (`train.csv`, target `SalePrice`, log-transformed), compared on accuracy and training time.
- **Stacked ensemble** — Random Forest, XGBoost and a neural network as level-0 base learners with out-of-fold predictions, combined by a Ridge regression meta-learner at level 1.

**Notebook:** `gradient_boosting_and_stacking.ipynb`
**Data:** Ames House Prices (`train.csv`)
