# Lab 07 — Federated learning & MLOps

- `federated_learning_differential_privacy.ipynb` — **federated averaging** simulated with [Flower](https://flower.ai/) on MNIST with non-IID client splits, compared against a centralized baseline; **differential privacy** experiments.
- MLOps pipeline for a wine classifier:
  - `data/wine.csv` versioned with **DVC** (`wine.csv.dvc`)
  - `train.py` — training with experiment tracking in **MLflow** (`mlflow ui --backend-store-uri sqlite:///mlflow.db`)
  - `export_model.py` → `model/` — exported model artifacts
  - `serve.py` — **FastAPI** inference endpoint (`uvicorn serve:app`)
  - `Dockerfile` — containerized serving

Standalone uv project (`uv sync`); example requests and commands in `commands.txt`. Assignment description in `a7.pdf`.
