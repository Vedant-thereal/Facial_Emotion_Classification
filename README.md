# Facial_Emotion_Classification
This repository contains a project in which I have built a Convolutional Neural Network to classify the Facial Emotions of the people in the pictures into the seven basic emotions,viz:
1. Anger
2. Disgust
3. Fear
4. Happiness
5. Neutrality
6. Sadness
7. Surprise

For the classification task, I have trained a few Convolutional Neural Networks on the facial emotions data on Kaggle(https://www.kaggle.com/datasets/samaneheslamifar/facial-emotion-expressions/code).\
The dataset contains roughly 35000 black and white images(28000 Training Images, 7000 Test Images) of size 48x48.\
For this purpose, various models have been trained of which most are overfitting the training data(test set accuracy ranging from 0.48-0.57)\
Of these models , model6 has the best accuracy of all Training Set Accuracy=0.83 , Test Set Accuracy=0.62\
Some observations on hyperparameters:
1. A slow Adam optimizer rate (~0.0001) gives a better accuracy than faster one.
2. ReLU activation for hidden layers works better than a Leaky ReLU activation.
3. No of epochs ~=15



