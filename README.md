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
