# nlp
This project compares the effectiveness in fake news detection between various ensemble classifiers and several vectorization models along with PCA features reduction. 

The code, first, based on https://github.com/ignasiusharvey/text_clustering/tree/master by Ignasius Harvey. Then, it was extended to do research on following questions:
* Do additional ensamble classifiers increase performance compared to a single classifier?
* Does PCA feature reduction improve the performance of classifiers?
* How does FastText do comparing to other vectorization models?
The compared calssifiers were:
* Random Forest
* K-Neighbors
* Multi-layer Perceptron
The compared ensemlbe classifiers were:
* bagging (different amounts of estimators)
* voting (hard and soft)
The compared vectorization models were:
* FastText
* Word2Vec
* GLOVE
* BERT
