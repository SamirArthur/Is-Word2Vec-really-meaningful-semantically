# Is Word2Vec really meaningful semantically?

## Approach for testing

What does English language look like if we print it on a 2D map; a clustering based on Word2Vec embeddings? Depending on the quality of the clusters (how much we are able to understand their meaning) we would be able to say 'Word2Vec describes language very well' or 'No Word2Vec is not reliable enough'. To be fair, this clustering actually will test how the model captures 'similarities' (syntagmatic and paradigmatic relations) rather then linear compositions (see the famous example below).

There are lots of great examples such as 'Queen = King + Woman - Man' illustrating how the model is good. We explore here a systematic testing on (almost) all English language in order to be able to assess the 'overall picture' hopefully.

## Test = Clustering of 300k words on top on SOM applied to Word2Vec embeddings

- Embeddings used: Google's Word2Vec model, source: https://code.google.com/archive/p/word2vec/ and SLIM version: https://github.com/eyaler/word2vec-slim

- SOM: Self-Organised Maps from Sompy package

- Clustering: k-means on top of the SOM map

## Results

Have a look at the inforgrafic in this repository:)
