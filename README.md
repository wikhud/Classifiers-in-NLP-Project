# Classifiers in NLP Project
This project compares the effectiveness in fake news detection between various ensemble classifiers and several vectorization models along with PCA features reduction. 

The code, first, based on https://github.com/ignasiusharvey/text_clustering/tree/master by Ignasius Harvey. Then, it was extended in order to do research on following questions:
* Do additional ensamble classifiers increase performance, comparing to a single classifier?
* Does PCA feature reduction improve the performance of classifiers?
* How does FastText do, comparing to other vectorization models?

The compared calssifiers are:
* Random Forest
* K-Neighbors
* Multi-layer Perceptron

The compared ensemble classifiers types are:
* bagging (different amounts of estimators)
* voting (hard and soft)

The compared vectorization models are:
* FastText
* Word2Vec
* GLOVE
* BERT
