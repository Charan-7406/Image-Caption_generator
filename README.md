# Image-Caption_generator
Image Captioning is the process of generating textual description of an image. It uses both Natural Language Processing and Computer Vision to generate the captions. It uses Artificial neural networks such as CNN and RNN.The model was trained on Flickr8k image dataset.Since the model was only trained on jpg image dataset, the model can take only jpg image as an input.
The 2 pretrained models used here are:
            1. inceptionV3 model which is trained on imagenet dataset
            2. GloVe model which is an unsupervised learning algorithm. 
            
 
 # System requirements
 A good CPU and a GPU with atleast 8GB memory
 Atleast 8GB of RAM
 Active internet connection so that keras can download inceptionv3/vgg16 model weights and also glove model.
 If the system gpu not good enough use google colab.
 
 #required libraries for python
* Keras 
* Tensorflow 
* tqdm
* numpy
* pickle
* PIL
* glob
* tqdm
 #for deployment i have used streamlit:
 streamlit
 
 #dataset
 Flicker8k dataset: https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip
 Flicker8k text : https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip
 
 #examples of the model genearting captions for test images:
 
 
 

