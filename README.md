# Comment-Sentiment-Analysis
Sentiment analysis on an amazon food dataset.

In this repository there are different models that analyze the opinion left by travelers on twitter. The data has been taken from a [competition in Kaggle](https://www.kaggle.com/c/spanish-arilines-tweets-sentiment-analysis/overview) carried out by a Spanish areoline. The data has been processed and various techniques have been tried for its processing.

## Text mining

- Tokenizer: [punkt](https://www.nltk.org/_modules/nltk/tokenize/punkt.html)
- [WordNet](https://wordnet.princeton.edu/): is a large lexical database of English. Nouns, verbs, adjectives and adverbs are grouped into sets of cognitive synonyms (synsets), each expressing a distinct concept. Synsets are interlinked by means of conceptual-semantic and lexical relations.

## Machine Learning

- Bag of words([TF-idf and Boolean model](https://en.wikipedia.org/wiki/Bag-of-words_model))
- Decision Tree
- Random Forest
- AdaBoost


## Deep Learning

- Word Embedding([Word2Vec](https://en.wikipedia.org/wiki/Word2vec))
- [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory): Long short-term memory.

## Results

### Boolean Model

| Model                           | Precision(%) | Macro Avg(%) | Weighted Avg(%) |
|---------------------------------|--------------|--------------|-----------------|
| DF + no processing data         |      33      |      20      |        38       |
| RF + no processing data         |      63      |      17      |        51       |
| **AB + processing data**           |      **64**      |      **18**      |        **51**       |
| DF + processing data            |      30      |      18      |        35       |
| RF + processing data            |      53      |      20      |        49       |
| AB + processing data            |      55      |      19      |        49       |
| DF + processing data + balanced |      20      |      20      |        20       |
| RF + processing data + balanced |      24      |      22      |        22       |
| AB + processing data + balanced |      22      |      17      |        17       |

### TF-idf Matrix

### Deep Learning


## Technologies and Libraries

- [Python](https://www.python.org/) 🐍
- [Sklearn](https://scikit-learn.org/stable/) 🧮
- [Keras](https://keras.io/) ❤️
- [NLTK](https://www.nltk.org/) 📝
