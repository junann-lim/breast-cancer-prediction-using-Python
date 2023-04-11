# Breast Cancer Classification

In this study, the support vector machine (SVM) and artificial neural network (ANN) machine learning models were developed to assist medical professionals in diagnosing and classifying breast cancer. Three datasets were used to train the machine learning models, which are the Wisconsin Breast Cancer Diagnostic (WBCD), Wisconsin Breast Cancer Original (WBCO), and Breast Cancer Coimbra (BCC) datasets. The feature extraction techniques, principle component analysis (PCA) and linear discriminant analysis (LDA), were also applied to all the datasets to reduce the dimensionality of datasets. The machine learning models were then trained with the original datasets, and the dimensionality-reduced datasets. The datasets were also split into the training set and the test set, with an 80:20 ratio. This is to ensure that the model is not simply memorising the training data, but is actually learning to generalise to new data. This is crucial to prevent overfitting of the models. 

Based on the results obtained from this study, the SVM model with RBF kernel demonstrated the best performance as compared to all the other SVM and ANN models. This conclusion was made as in general, the SVM model with RBF kernel outperformed all the other models, including the ANN model for every dataset. Besides, the SVM model with RBF kernel also showed its versatility as it performs well, in general, using different breast cancer datasets with different dimensionality. Besides, it can also be concluded that applying feature extraction methods to reduce the dimensionality of the datasets does not necessarily improve the performance of the machine learning models. 
