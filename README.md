# Recommendation-System-using-NCF

- Implemented research paper with changes i.e. adding dropout layer after embedding layer and adding dropout layer after concatination of 
  MLP and MF layers. This gave better results than original paper.

- Dataset - https://grouplens.org/datasets/movielens/100k/
- Preparing and Labeling the dataset, splitting data, normalizing.
- Defining dcg and ndcg metrics.
- Preparing matrix factorization, applying early stopping after investigation.
- Building multi layer perceptron model, neural collaborative model, and evaluating each model wrt. to their accuracy.
