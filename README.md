## Amazon-fine-food
This is the end to end machine learning project executed as part of my learning journy of natural language processing

## Problem Statement

## Purpose of the Project
This dataset has customer reviews about the foods they have purchased. Reviews means all text data. This is one of the popular dataset where data practitioners perform
their experimentations. I have used this understand the basic text pre-processing.
### preprocessing techniques
- Converting text to lower case
- Remove unncessary spaces in the beginning or end of each sentence
- Remove html tags from data using beautifulsoup
- Remove all the punctuations
- Expand all the contranctions in the English language.
- Remove or convert the numbers to some representation (using regex)
- Remove all stopwords
  * problems with mindless stopword removal
- Convert the words to their bases (lemmatization and stemming)
After text preprocessing I have used mupltiple Natural Language Processing Tool Kit (NLTK) methods to convert text data to numerical vectors. 
These Numerical data will help me to understand the polarity thereby I can use different classification of the dataset.

### Text to Numerical vector conversion methods
- Bag of words (BOWs) (in sklearn count vectorizers)
    * problems with BOWs
    * different types of Bag of words
- Term frequency Inverse document frequency (Tf-Idf)
    * How Tf-Idf works more better than BOWs (comparitive study)
    * Sparse representation of the Tf-Idf vectors
    * Vocabulary representations
    * problems with tfidf
- Word2vec representation of text
    * Comparison between Tf-Idf and Word2Vec
    * fixed vector length representation
    * types of word2vec
 
