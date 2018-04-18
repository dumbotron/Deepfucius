# Deepfucius: https://twitter.com/deepfucius
A basic LSTM RNN twitter bot for non-election altering use

Inspired by Jason Brownlee's blog posts https://machinelearningmastery.com/how-to-develop-a-word-level-neural-language-model-in-keras/

Contains:
1. Create_GloVe_Vectors.ipynb -- Generates glove vectors from a corpus of text.
2. Clean_Data.ipynb -- Cleans data and creates training set.
3. DeepFucius_Model.ipynb -- Trains LSTM Model.
4. Generate_Texts.ipynb -- Randomly generate texts from model weights.
5. Tweet.ipynb -- Periodically tweets texts from Generate_Texts output.


Blog post is on its way.

Future versions to include:
1. Beam search implementation in text generation
2. Different model architectures
3. Interactions with other users in the Twittersphere
4. Generate topical responses to tweets abt Confucius and DM or @users
