
## Emotion Detection  Using Recurrent Neural Networks
Emotions Detection is an interesting blend of Psychology and Technology. Emotion detection enables machines to detect various emotions. The technique that helps machines and computers to be capable of detecting, expressing and understanding emotions is known as emotional intelligence. In order to understand and detect emotions, the first and foremost requirement for Deep Learning Models such as Recurrent Neural Networks, Bi-LSTM and GRU is the availability of a dataset. Here, we will Emotions Sensor Data Set Contain Top 23 730 English Words Classified Statistically into 7 Basic Emotion Disgust, Surprise ,Neutral ,Anger ,Sad ,Happy and Fear.
## Implementation Process
- We are using a dataset which contains some text data along with the emotion expressed in a given text which is used as label. Training our data with the given dataset , our objective is to build a model which will predict the emotion of a text with a decent accuracy.

- This Technology Helps to Build a Companion machines such as Robots, thus Robots Can be Friendly and Have The Ability to Recognize Users Emotions, reply and to Act Accordingly.

## Tools
- Programming Language: Python.
- Pandas
- Matplotlib
- Numpy
- Torch
- Torchtext
- CUDA  
## Dataset
Here we have 16000 data for training and 2000 data for validation and testing as our data set with two column. Column 1 contains the text and column 2 contains the emotion of the text as label. Here our target is to classify a sample text among the 6 emotion classes we used as labels such as Joy, anger, sadness, love, fear and surprise. Here we convert the text data into numerical data through tokenizing. After converting to numerical data we run Bi-directional LSTM and GRU to extract sequencial information from the data and creating models and checking all their accuracy.
## Classification Accuracy
- Bi-LSTM Test Accuracy: 88.4%
- GRU Test Accuracy    : 88.6%