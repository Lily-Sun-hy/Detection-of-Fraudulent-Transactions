# Detection-of-Fraudulent-Transactions

This project trains a Gaussian mixture model using an open-source credit card fraud dataset to detect anomalous transactions (binary classification). 

The project involves tasks including exploratory analysis, identifying class imbalance, training and optimizing Gaussian models. The training process consists of experiments with variables identified as:
1. Number of feature(s) used for training
2. Number of Gaussian distributions used for trainning
3. Use of class labels (supervised/semi-supervised/unsupervised)

The experiments performed are but not limited to:
- Training with a single feature and a single Gaussian distribution in an unsupervised manner (class labels are not used for training)
- Trianing with a single feature and a single Gaussian distribution in a semi-supervised manner (class labels are used but are used altogether)
- Training with a single feature and a single Gaussian distribution in a supervised manner (class labels are used and each class is used separately)
- Training with a single features with multiple Gaussian distributions
- Trianing with multiple features and multiple Gaussian distributions
- ...

The model performance is evaluated using ROC-AUC and optimized using F1 score.

In the end a total of 13 models are used and the one with the best performance is used on the testing data. The resulting precision score is 0.8720. The resulting recall score is 0.7515. The maximum F1 score is 0.8015.
