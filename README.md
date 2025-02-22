# Detecting-Infected-Patients-Using-CNN

1. Article Introduction
In the article used for this exercise, an X-ray image of the lungs of COVID-19 patients and healthy individuals is used to design a Convolutional Neural Network (CNN). Given
the life-threatening nature of this disease, training a network with high accuracy is of great importance. You can download the article from this link:
https://onlinelibrary.wiley.com/doi/epdf/10.1155/2021/6621607

2. Data Collection and Image Preprocessing 
In the data collection section, the method of collecting data is explained. This dataset has been provided for you to get started. Therefore, for this part, you will begin with
preprocessing the data. To preprocess the data, according to the explanation in the article, perform the following: Implement four types of data augmentation step by step.
It is recommended to do this in such a way as to prevent overfitting in the network. This means you should first apply the first type to the dataset,
then train the network and analyze the results. Repeat the process for the second type, and so on. Also, perform normalization as described.

3. Network Training 
Train the CNN based on the provided descriptions. Implement the network and train it on the training data. Plot the Accuracy and Loss charts for the training and validation data.

4. Network Evaluation 
Evaluate the trained network on the test data and report the evaluation metrics, including Accuracy, Precision, Sensitivity, Specificity, and F1 score. Also, plot the confusion
matrix. Do not forget that, in the article, the preprocessing stage was performed under the supervision of a medical expert for data selection. Since we cannot perform this step, 
your network may perform differently compared to the article.

5. Extra Network Evaluation 
Report the accuracy of the network based on the first column of Table 6 for tests with different numbers of layers for the network. Keep in mind that it is necessary to train and
test the network each time.
