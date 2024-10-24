# akbankderinogrenmebootcamp
Fish Classification by ANN in Python With A Large Scale Fish Dataset

Project Url: https://www.kaggle.com/code/osmankaraahmetolu/fish-classification-by-ann

Kaggle Dataset Url: https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset

In this analysis, an ANN model is designed to classify 9 different class of fishes by using Kaggle Dateset of A large Scale Fish Dataset.
Images from this dataset are splitted into two datasets, which  ara 80% for training, 20% for validation.
This fish data ara visualized by bar and donut graphics.

In this study, thirteenth layer ANN is constructed, by using sequential model with Input, Flatten, Dense, BatchNormalization, Dropout layers.
Relu and softmax activation functions are integrated into the model. The model is tried in 32 epoch and use 64*64 image resolution.

The model generate estimates with 0.7302 accuracy, 0.7270 loss, 0.7572 val_accuracy, 0.8878 val_loss.

At last hyperparameter tuning is made and the values of best learning rate of 0.0006361252779797229
and best activation function of relu.

