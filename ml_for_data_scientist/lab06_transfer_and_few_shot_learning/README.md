# Lab 06 — Transfer & few-shot learning

- `transfer_learning_resnet50.ipynb` — cat-vs-dog classifier from only 1000 training images by fine-tuning **ResNet50**: frozen backbone vs partial vs full fine-tuning vs training from scratch (96–99% vs ~50% test accuracy).
- `few_shot_prototypical_networks.ipynb` — **Prototypical Networks** on Omniglot: episodic training, embedding network, N-way K-shot evaluation on unseen classes, t-SNE of the embedding space.

Standalone uv project (`uv sync`). The cats-vs-dogs images (subset of [Kaggle Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats)) are expected in `data/{train,val,test}/{cat,dog}/` (git-ignored due to size); Omniglot downloads automatically. Assignment description in `a6f.pdf`.
