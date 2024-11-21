### Decision Tree: 
- non-lazy, builds model during training
- easy to see where splits are made
- prone to overfitting
### KNN:
- lazy, makes predicitons at run time
- no explicit model
- sensitive to noise, irrelevant features, and scalability issues for large data sets.


DT: fast training and prediction
KNN: no training, slow prediction (calculats distance to ALL POINTS) time complexity of O(n*m)

DT: handles numerical and categorical and misisng data
KNN: must use numberical features and standardized. missing values must be handled during preprocessing.

Conclusion: Decision Tree is more suited for problems where interpretability and speed are important, especially when you deal with both numerical and categorical data.
KNN is a powerful, simple model but suffers in computational complexity for large datasets and needs careful preprocessing of data (like normalization).