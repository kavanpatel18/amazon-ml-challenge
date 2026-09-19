# Amazon ML Challenge - Large-Scale Product Classification

Large-scale product-category classification using multilingual text preprocessing, 384-dimensional sentence embeddings, GPU-accelerated nearest-neighbor classification, and majority-vote ensembling.

## Problem

Predict the product `BROWSE_NODE_ID` from `TITLE`, `DESCRIPTION`, `BULLET_POINTS`, and `BRAND`.

The project works with roughly 2.9 million products and approximately 9,900 categories.

## Pipeline

```text
Raw product metadata
       |
       v
Text cleaning + normalization
       |
       v
Sentence-Transformer embeddings
       |
       v
GPU-accelerated KNN
       |
       v
Multiple predictions
       |
       v
Majority-vote ensemble
       |
       v
Submission
```

## Result

The original project records a best submission accuracy of **66.85%**.

## Project structure

```text
notebooks/
  amazon-ml-preprocessing.ipynb
  amazon_ml_translation_csv.ipynb
  amazon_ml_embeddings.ipynb
  amazon_ml_training.ipynb
  amazon_ml_mode.ipynb
leaderboard/
submission_top-score.csv
```

Competition datasets are not included. Download the permitted competition data separately and update notebook paths.

## Tech stack

Python, pandas, NumPy, scikit-learn, Sentence-Transformers, CuPy/GPU acceleration, and ensemble learning.
