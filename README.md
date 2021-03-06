# Compare Next Word Prediction Using GRU and RNN models

by Group: 466_Project (Chenge Liu, Tingyang Jiao, Hao Gu, Kaiwen Zhang, Qian Zhao)

<p align="center"><img width="100%" src="model.gif" /></p>

## About this Project

> Predicting the next word based on the earlier text still is a big problem to research. Additionally, prediction problems are the basic aspect in many certain problems in the NLP area. Therefore, this prediction problem is really important and valuable in both research and practical area.

> In our project, we will concentrate on the different probability distributions over the next word prediction given by two famous language models. The reason for choosing those two methods is that the RNN method shows a good ability when facing a short sequence prediction problem but has only short-term memory. In the contrast, GRU model is a new format of the LSTM model, which has a good ability to deal with long sequence prediction problems.

## We follow this tutorial to constrcut our models

> Rizvi, Mohd Sanad Zaki. "A Comprehensive Guide To Build Your Own Language Model In Python!". Medium, 2019, https://medium.com/analytics-vidhya/a-comprehensive-guide-to-build-your-own-language-model-in-python-5141b3917d6d.

## How to use the project

- Download the file: model_now.ipynb
- Open it on Jupyter Notebook or Colab
- If you want to change the model, uncomment the line "SimpleRNN" and comment the line "GRU"

<p align="center"><img width="100%" src="modify_models.png" /></p>

- Run the code till the 3rd from last part ("define the model") to get graphs
- Run the code till the end to generate output by the trained model (By default the maximum input length is 30 letters including the blank space)
