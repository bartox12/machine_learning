# ML for Data Scientists

Lab assignments from an advanced machine learning course (in English). Labs 05–07 are standalone [uv](https://docs.astral.sh/uv/) projects — each contains its own `pyproject.toml` and `uv.lock`; run `uv sync` inside the lab folder to reproduce the exact environment.

## Contents

| Lab | Topic | Highlights |
|-----|-------|------------|
| [02](lab02_model_interpretability) | Model interpretability | SHAP (TreeExplainer, beeswarm, dependence & force plots) on a Random Forest trained on Adult Income; LIME explanations for a pretrained ResNet50 |
| [03](lab03_probabilistic_ml) | Probabilistic ML & time series | Bayesian linear regression in PyMC with MCMC diagnostics, Gaussian Process regression, ARIMA modelling of Apple stock prices |
| [05](lab05_generative_models) | Generative models | Variational Autoencoder from scratch (Fashion-MNIST), DCGAN on CIFAR-10 with FID tracking, VAE-based anomaly detection |
| [06](lab06_transfer_and_few_shot_learning) | Transfer & few-shot learning | ResNet50 transfer learning on 1000 images (cats vs dogs), Prototypical Networks with episodic training on Omniglot |
| [07](lab07_federated_learning_mlops) | Federated learning & MLOps | Federated averaging with Flower, differential privacy, full MLOps pipeline: DVC, MLflow, model export, FastAPI serving, Docker |
