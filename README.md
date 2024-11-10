# NLP_StopWordandLemmatizationandStemmingFromTextInput
This program preprocesses text by removing stop words and applying either lemmatization, stemming, or both based on user choice.

This Python program tokenizes a user-input text, removes stop words, and allows the user to choose between lemmatization, stemming, or both for processing.
Steps:
1. Setup and Downloads: Ensures necessary NLTK resources for tokenization, stop words, and word lemmatization are downloaded.
2. User Text Input: Prompts the user to input the text to be processed.
3. Choice Input for Processing: Asks the user to select between lemmatization ('lemm'), stemming ('stem'), or both ('both').
4. Tokenization: Splits the input text into individual tokens (words).
5. Stop Word Removal: Filters out common English stop words from the tokenized list to focus on meaningful words.
6. Initialization of Lemmatizer and Stemmer: Initializes both the lemmatizer (WordNet Lemmatizer) and stemmer (Porter Stemmer).
7. Processing by User Choice:
      Lemmatization ('lemm'): Applies lemmatization to each filtered word and prints the lemmatized list.
      Stemming ('stem'): Applies stemming to each filtered word and prints the stemmed list.
      Both ('both'): First applies lemmatization, then stems the lemmatized words, and prints both results.
Output: Prints the filtered words without stop words, the lemmatized list, and the stemmed words (if chosen) based on the user's selection.
