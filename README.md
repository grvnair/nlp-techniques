# nlp-techniques

Built a Spam Classifier using different Vectorization techniques in NLP.

Project Pipeline:
1. Data Collection
2. Tokenize
3. Clean text
4. Vectorize
5. Machine Learning/Deep Learning Algorithm
6. Evaluate Metrics


TF-IDF

1. Simple document vectors that represent how important a word is to a document within a corpus.
2. No consideration of context in which a word is used.
3. Creates very sparse, large vectors.

Word2vec

1. Word vectors created through a shallow, two-layer neural network: word vectors can then be averaged or summed to create document level vectors.
2. Creates smaller, dense vectors.
3. Word vectors do have context built in.

TF-IDF creates sparse matrices with lots of zeros, Word2vec is opposite as it creates very dense non-zero vectors.

Doc2vec

1. Document vectors created through a shallow, two-layer neural network.
2. Creates smaller, dense vectors.
3. Document vectors have context built in.

Recurrent Neural Network

1. A type of neural network that has an understanding of the data’s sequential nature (forms a sense of memory).
2. Dense vectors are created within the model.
