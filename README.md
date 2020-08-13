# Visualizing Word Embeddings using Google's embedding projector
Why import the TSNE package in your Python environment when a few simple steps can give you way more interaction and FUN with your data? Thanks to Google we can see how our textual data is being used to find out how words are simimlar in how they were written. 


# Objective
Our objective is to analyze text data, as in qualitative data, i.e. Research papers, tweets, texts, etc. In order to do that you need these things called Word Embeddings. This is taking words from a particular dataset and turning them into meaningful numbers that can be plotted on a graph(aka vector)

# Purpose
- Computers cannot understand words 
- It brings meaning to how words are being used
- It is super fun

We do this because computers cannot understand words, they only know numbers, so if you want to run any sort of analysis on text data you have to turn it into numbers. Instead of randomly assigning each word in a text a number or counting them, it makes sense to turn these words into **meaningful** numbers so that way when we run an analysis on how words are being used we can see how different they are or similar in your data. 

# Implementation

There are multiple ways of doing this, a way that I did it was downloading a pre-trained word embedding model called GloVe, that can create those meaningful vectors for you. There are other ones besides GloVe). 
GloVe embedddings(https://nlp.stanford.edu/projects/glove/), downloadable code is in Python file.

My motivation behind this was once you build your deep learning algorithim, it really makes sense to see how your data interacts and so why would I use something like this:<br />

<div align="center">![Alt text](scatter.png?raw=true "Title") </div>
When I can use something like this: <br />

<div align="center">![Alt text](embGIF.gif?raw=true "Title")</div>




