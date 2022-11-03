The objective of this project is to implement the Word2vec approach. 

The model was introduced in Mikolov et al. 2013 (https://arxiv.org/pdf/1301.3781.pdf). It is one of the most successful ideas for learning an embedding matrix from a corpus. 

The model captures some linguistic patterns between word vectors and performs well on the word analogy task.

For instance, the embedding vectors learned using the word2vec approach have the following property:
$e_{France} - e_{Paris} = e_{England} - e_{London}$ (where $e_X$ stands for the embedding of the word X).

The project is divided into four parts:

- Part 1: introduce the concept of word embedding and the word2vec approach.
- Part 2: load the dataset and perform the first processing steps in order to get the corpus.
- Part 3: use the processed corpus to create a dataset for a binary classification problem.
- Part 4: create an embedding matrix by learning the parameters of a shallow neural network trained for the binary classification task.
