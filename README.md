# friends-word2vec
Training word2vec on the script for the TV show "Friends"

This project demonstrates the use of Gensim's Word2Vec model to 
generate word embeddings from the scripts of the popular TV show *Friends*. 
The embeddings capture semantic relationships between words in 
the context of the show's dialogue.

It uses nltk for preprocessing the script. This includes tokenization,
removal of stopwords, and Gensim's simple_preprocess method.

Words used in similar context have high vector similarity.
