# Machine Learning

Solutions to lab assignments from a university Machine Learning course. Each lab lives in its own folder as a Jupyter notebook, together with a short README describing its scope. Notebook comments are written in Polish.

## Contents

| Lab | Topic | Highlights |
|-----|-------|------------|
| [01](lab01_data_preprocessing) | Data preprocessing | EDA, missing values, scaling, one-hot encoding, train/test split |
| [02](lab02_clustering) | Clustering | k-means implemented from scratch (k-means++ init), KMeans / Agglomerative / DBSCAN, silhouette score, customer segmentation |
| [03](lab03_linear_logistic_regression) | Linear & logistic regression | OLS implemented from scratch, regression metrics, sigmoid, Titanic survival classification |
| [04](lab04_trees_and_ensembles) | Trees & ensembles | Decision trees, random forest, AdaBoost, gradient boosting, XGBoost |
| [05](lab05_svm) | Support Vector Machines | Linear SVM trained from scratch, kernels, cross-validation, GridSearchCV |
| [06](lab06_dimensionality_reduction) | Dimensionality reduction | PCA, LDA, eigenfaces on the LFW face dataset |
| [07](lab07_pytorch_neural_networks) | Neural networks (PyTorch) | Tensors, regression & classification nets, activation functions, Adam vs SGD, overfitting |
| [08](lab08_nlp_sentiment_analysis) | NLP: sentiment analysis | IMDB reviews, text cleaning with NLTK, TF-IDF, logistic regression |

## Data

The `data/` folder contains the datasets loaded from disk by labs 01–03:

- `titan.csv` — [Titanic](https://www.kaggle.com/c/titanic) passenger data
- `housing.csv` — [California Housing](https://github.com/ageron/handson-ml2/tree/master/datasets/housing)
- `Mall_Customers.csv` — [Mall Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

The remaining labs use datasets built into scikit-learn or downloaded at runtime.

## Setup

```bash
pip install -r requirements.txt
jupyter lab
```
