# Breast-cancer-prediction-using-Artificial-Neural-Network-by-Keras
Downstream of Deep Learning


# Description of the dataset:
Breast cancer is the most common form of cancer affecting women worldwide, accounting for 25% of all reported cancer cases. In 2015, it impacted more than 2.1 million individuals. The disease initiates when cells within the breast undergo uncontrolled growth. Typically, these cells manifest as tumors that can be detected through X-ray imaging or palpated as abnormal masses in the breast region.



# Objectives:
1. Understand the dataset and its features
2. Data Pre-processing/EDA
3. Build up the artificial neural network by using Keras to predict whether the cancer type is malignant or benign.


# Result:
Loss measures the error or mismatch between the predicted output of the model and the true output. In this case, the loss value for the training data is 0.0081, which is quite low. A lower loss indicates better performance, as it means the model's predictions are closer to the actual values. Accuracy represents the proportion of correctly classified instances out of the total number of instances. A value of 1.0000 indicates that the model has achieved perfect accuracy on the training data. However, it's important to note that high accuracy on the training data doesn't guarantee similar performance on unseen or validation data. The validation loss measures the error on a separate dataset that was not used for training. In this case, the validation loss is 0.0987, which is higher than the training loss. This indicates that the model may be slightly overfitting the training data, as it performs slightly worse on unseen data. The validation accuracy represents the accuracy of the model on the validation dataset. It is calculated similarly to the training accuracy but on unseen data. The value of 0.9825 suggests that the model is performing well on the validation data, but not as perfectly as on the training data. Overall, the model seems to have achieved excellent accuracy and relatively low loss on the training data. However, it is important to monitor the performance on unseen data (validation set or test set) to ensure that the model generalizes well and doesn't overfit to the training data.
