# Multimodal data fusion for Alzheimer’s disease diagnosis

This project aims to  perform multi-class classification (Control Normal, Mild Cognitive Impairment, Dementia) model by fusing multiple modalities like neuroimaging data like PET, MRI and neuropsychological assessment data such as MMSE data to predict Alzheimer’s at its onset. The project involves investigation of various machine learning strategies to perform feature selection such as Lasso and Ridge to identify relevant features for the MRI dataset merged with MMSE data. Univariate feature selection approach has been to select the best features for PET data merged with MMSE data.

## MRI+MMSE data fusion
First, we concentrate on MRI+MMSE dataset and apply SGD model using l1 nd l2 penalty for feature selection as the number of features in MRI dataset is 321.

## PET+MMSE data fusion
Second, we work on PET+MMSE data and apply different classifiers like Gaussian Naive Bayes, Decision Tree Classifier, Support Vector Machine anf carry out a comparison.

## Early and Late fusion
Finally, we merge the best perfroming model in both MRI+MMSE and PET+MMSE model in an ensemble model to by performing late and eearly fusion of features to evaluate the performance metrics. In order to improve the model accuracy, an ensemble model with a voting classifier using a soft voting approach was created.
