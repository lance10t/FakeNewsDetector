# FakeNewsDetector
Exploring various approaches to develop a trained model for Fake News detection

This project was developed as part of a submission for the Jump Start Deep Learning course conducted by [Red Dragon AI](http://reddragonai.com/)

# Project objectives
This project implements a binary text classification model for Fake News Detection.  The data set was made available from Kaggle.  In this project, I experimented with a few points as part of the learning process, namely:

1.  Effect of data biases on the quality of the model generated
2.  Effectiveness of a simple Logistic Regression model that fitted well to the data, but failed with the out-of-set data, partially due to data biases introduced.
3.  Approaches to clean up the data to be neutral
4.  Implement an LSTM model with both clean and biased data to compare and contrast the importance of having representative data - this is an important lesson as a model effectively learns what we feed it, including racial, gender, and demographic biases.
