# DisneyLorcanaStuff
--------------
Thoughts:

Explain card game and motivation

Explain attributes of a card

Explain attributes of a deck

Explain the goal of the model

Build a deck

Also look(EDA) at card data

Explain why NLP is good - next CARD prediction

First tried regular NLP-type things, LSTM, transformer

Ran into issues → predicts the same card over and over because of the way decklists are formatted

Tried shuffling → still same issue - can it be resolved with setting the card max to 4, but that’s lowkey cheating
Considered bag of words

Using ngrams → issue again is that the closest cards are the same, so get lots of repeat → its better though!!!

Tried shuffling, then we get repeats of cards later on, so not in order, but still issue


--------------
References:

https://betterprogramming.pub/generating-pok%C3%A9mon-cards-from-scratch-using-gpt-and-stable-diffusion-32f1a85ae2ac 

https://github.com/rbelfer/pokedex_nlp

https://medium.com/analytics-vidhya/predicting-pok%C3%A9mon-type-with-the-pok%C3%A9dex-7038754dc422

https://www.kaggle.com/datasets/emilhvitfeldt/lorcana-cards 

Stemming and lemmitization  : https://medium.com/coinmonks/multi-label-classification-blog-tags-prediction-using-nlp-b0b5ee6686fc

Magic : https://towardsdatascience.com/artificial-intelligence-in-magic-the-gathering-4367e88aee11

Understanding the black box !!

https://strikingloo.github.io/k-means-clustering-magic-the-gathering 

https://lorcania.com/popular 
