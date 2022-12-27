# nlp-techniques

TF-IDF

•	Simple document vectors that represent how important a word is to a document within a corpus.
•	No consideration of context in which a word is used.
•	Creates very sparse, large vectors.

Word2vec

•	Word vectors created through a shallow, two-layer neural network: word vectors can then be averaged or summed to create document level vectors.
•	Creates smaller, dense vectors.
•	Word vectors do have context built in.

TF-IDF creates sparse matrices with lots of zeros, Word2vec is opposite as it creates very dense non-zero vectors.

Doc2vec

•	Document vectors created through a shallow, two-layer neural network.
•	Creates smaller, dense vectors.
•	Document vectors have context built in.

Recurrent Neural Network

•	A type of neural network that has an understanding of the data’s sequential nature (forms a sense of memory).
•	Dense vectors are created within the model.
