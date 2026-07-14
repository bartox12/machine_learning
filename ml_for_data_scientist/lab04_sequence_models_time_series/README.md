# Lab 04 — Sequence models for time series

Recurrent and attention-based forecasting, benchmarked against classical time-series methods.

- **Sequence-to-one LSTM** baseline forecasting household appliance energy use, with hyperparameter sweeps over the look-back window (12/24/48 steps) and hidden size.
- **Sequence-to-sequence LSTM** predicting a multi-step horizon, illustrating the expected error growth as the horizon lengthens.
- **Classical baselines** — ARIMA(2,1,2) and Prophet — evaluated on the same test set for a fair comparison.
- **Attention mechanisms** on top of the LSTM encoder, with visualization and analysis of the learned attention weights (a strong recency bias).
- **Rossmann store sales** as a second application (Problem 3), using the store metadata and sales history.

**Notebook:** `lstm_attention_forecasting.ipynb`
**Data:** UCI Appliances energy (`energydata_complete.csv`) and Rossmann store metadata (`store.csv`). The 38 MB Rossmann sales file (`train.csv`) is git-ignored — download it from the [Rossmann Store Sales Kaggle competition](https://www.kaggle.com/c/rossmann-store-sales). Assignment description in `a4.pdf`.
