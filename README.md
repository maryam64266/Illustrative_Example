# A Survey and Illustrative Example of Hybrid Semantic and Contextual Models for Improving Diversity and Accuracy in Personalized Tag Recommendation

## Overview
This repository provides an illustrative implementation accompanying the paper
**“A Survey and Illustrative Example of Hybrid Semantic and Contextual Models for Improving Diversity and Accuracy in Personalized Tag Recommendation.”**

The code demonstrates a hybrid tag recommendation framework combining:
- Collaborative Filtering (CF)
- Content-Based Filtering (CB)
- Context-Aware (CA) modelling
- Sentiment-aware components

The implementation is provided as Jupyter notebooks for clarity and reproducibility.

---

## Repository Structure
- `data_loading.ipynb`  
  Initial dataset loading and preparation using the MovieLens dataset.

- `tag_process.ipynb`  
  Pre-processing steps and user–item subset construction.

- `sentimentMod.ipynb`  
  Collaborative filtering model implementation.

- `sentiment_label.ipynb`  
  Sentiment labelling component integrated into the CF model.

- `content_based.ipynb`  
  Content-based filtering model.

- `context-aware.ipynb`  
  Context-aware recommendation model.

- `evaluation_fold.ipynb`  
  Final tag recommendation generation and evaluation.

---

## Execution Order
For reproducibility, notebooks should be executed in the following order:

1. `data_loading.ipynb`  
2. `tag_process.ipynb`  
3. `sentiment_label.ipynb`  
4. `sentimentMod.ipynb`  
5. `content_based.ipynb`  
6. `context-aware.ipynb`  
7. `evaluation_fold.ipynb`

---

## Requirements
- Python 3.x  
- Jupyter Notebook  
- Common scientific libraries (e.g., NumPy, Pandas, Scikit-learn)

Specific library versions can be inferred from the notebooks.

---

## Data Availability
Due to ethical and licensing constraints, the MovieLens dataset is **not included** in this repository.

Researchers can obtain the dataset from:
https://grouplens.org/datasets/movielens/20m/

---

## Dataset Reference
F. Maxwell Harper and Joseph A. Konstan.  
*The MovieLens Datasets: History and Context.*  
ACM Transactions on Interactive Intelligent Systems (TiiS), 5(4), 2015, Article 19.  
https://doi.org/10.1145/2827872

---

## Reproducibility Statement
This repository is provided to support reproducibility of the proposed methodology.
All preprocessing, modelling, and evaluation steps are fully documented in the notebooks.

