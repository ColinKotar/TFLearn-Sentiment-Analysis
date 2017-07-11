# TFLearn-Sentiment-Analysis
Sentiment analysis using TFLearn (a high-level library built on top of TensorFlow)

## My Neural Network Model
Input Layer: 10,000

FC Layer: 256, ReLu activation

FC Layer: 64, ReLu activation

FC Layer: 8, ReLu activation

OuputLayer: 2, Softmax activation

Regression: optimizer='sgd', learning_rate=0.1, loss='categorical_crossentropy'

Training: validation_set=0.1, show_metric=True, batch_size=100, n_epoch=200 (total)

## Results
Accuracy = 75%

Test Accuracy = 74%

# Handwritten Digit Recognition
Handwritten digit recognition (mnsit data set)

## My Neural Network Model
Input Layer: trainX.shape[1]
    
FC Layer: 192, ReLu activation

FC Layer: 64, ReLu activation

FC Layer: 16, ReLu activation
    
OuputLayer: 10, Softmax activation

Training: optimizer='adam', learning_rate=0.01, loss='categorical_crossentropy'

## Results
Accuracy = 99.6%

Validation Accuracy = 97.4%

Test Accuracy = 97.51%
