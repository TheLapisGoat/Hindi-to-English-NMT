# Hindi-to-English Neural Machine Translation
Created a seq2seq translation model using LSTMs with Luong Attention. Trained a Word2Vec model using the [IIT Bombay Hindi Monolingual Corpus](https://www.cfilt.iitb.ac.in/iitb_parallel) to generate Hindi word embeddings.
Used [pre-trained word vectors](https://nlp.stanford.edu/projects/glove/) for english. Trained the model on the [IIT Bombay Parallel Corpus](https://www.cfilt.iitb.ac.in/iitb_parallel/). Inference is done with Greedy Search.

Trained hindi word vectors are in [KeyedVectors.tar.bz2](./KeyedVectors.tar.bz2)

## Setup
Install all dependencies using `pip install -r requirements.txt`.
