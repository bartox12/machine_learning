# Lab 05 — Generative models

- `vae.ipynb` — **Variational Autoencoder** built from scratch in PyTorch, trained on Fashion-MNIST: reconstruction vs KL trade-off, t-SNE of the latent space, sampling from the prior, latent interpolation, ablations (reconstruction-only / KL-only).
- `dcgan.ipynb` — **DCGAN** on CIFAR-10: generator/discriminator architectures, training loop with loss curves and **FID** tracking (`dcgan_*.png` show progress, losses and final samples).
- `vae_anomaly_detection.ipynb` — unsupervised **anomaly detection** using VAE reconstruction error.

Standalone uv project (`uv sync`). Datasets download automatically via torchvision into `data/` (git-ignored). Assignment description in `a5.pdf`.
