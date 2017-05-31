# Recurrent-Neural-Networks
My own attempt of wrapping my mind around RNNs.

## Ultimate Goals
* To create a RNN agent that can play a game, like Tic-Tac-Toe
* To be able to teach the concept of RNNs to the point where one can implement in just Python's Numpy
* To provide the learning steps I took in learning RNNs (with a background in basic NN, CNNs, classification, regression).

## First Phase - RNN in just Numpy
Andrej Karpathy's Stanford Lecture **CS231n Winter 2016 Lecture 10 Recurrent Neural Networks, Image Captioning, LSTM** (sorry, the YouTube link is private and I'm not sure if I can share it).
I'm going through the Stanford lecture and parsing the lecture at my own pace. I'm creating a notebook that elaborates [Andrej's barebones implementation](https://gist.github.com/karpathy/d4dee566867f8291f086) of a RNN. My implementation is a notebook `min-char-rnn`.

In this notebook `min-char-rnn`, I added helpful comments that I wish I saw when I was first viewing the code. I played around with a few hyperparameters like the sequence length, and hidden layer length to get a feel for how the RNN behaves. I then uploaded a text document of over 26,000 characters -- the chat messages of a friend and I.

Here's the training loss over time and a sample output of the RNN (not very legible, but it became pretty good at consistently picking out dates of the messages.

![loss-graph](https://github.com/JLee21/Recurrent-Neural-Networks/blob/master/img/loss-graph.JPG)

```python
'''
 ay. AJ 10 MAm

Anoad.y?
Thet danp ening rillI Kwwand duck?
Oh in
No kengfon tal Stam 18:02PM

Okre dour...!?
Hy Ath, 41, 9:49PMP
danititt fnay sting kurs anelzz,
singe. lete vill
APR 19TH, 
 TH, 10:39PMM
MAR 19 beH wi Kay

Dam

I'lR 24TH, 9:35APMj Reall dainy
Dat. [S:26TH, Kraldebo dow do
Gon.
Oh'r
No ke fuke?
mmm?
Dat 22:38PM, 9:23.
stin illa your Khaleesi
lolnin
Ot tint bight
'''
```

## Second Phase - RNN in Keras
To be...

## Third Phase - RNN and LSTM
To be...

## RNN and Policy Gradients
To be...
