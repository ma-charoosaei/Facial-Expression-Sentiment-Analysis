# Facial-Expression-Sentiment-Analysis
An emotion detector for multi-faced real-time scenes

Face detection in this project is done in real-time using Haar cascades and then each face is classified into an emotion category. 
Sentiments are analyzed based on the VGG-Face model and cosine similarity used in Facebook's DeepFace framework. 
DeepFace is originally designed to handle the dominant face expression in the frame, but some modifications have been made to cope with multiple faces.

Here are the results on some randomly downloaded data with the given model. 

![](FaceSentiment.gif)

# Colab Notebook
The code needed to preprocess the data and train the model is available in the following notebook.
Set the runtime to GPU and run everything.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/ma-charoosaei/Facial-Expression-Sentiment-Analysis/Facial_Expression_Sentiment_Analysis.ipynb)
