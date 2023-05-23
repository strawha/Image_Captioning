## Image-Captioning

This is an Image Captioning system which takes Images as input and provides meaningful captions describing the Image.
The system is built from CNN + LSTM models, where CNN does the task of obtaining features from Images, i.e. it will 
convert Image to vector information. LSTM (Long Short Term memory) is a recurrent neural network that is capable of 
learning long term dependencies in data. We will be using it to learn / predict captions of the Input Image.

For training the model, we have used [Flicker Image Captioning Dataset] (https://www.kaggle.com/hsankesara/flickr-image-dataset)
