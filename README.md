Keyword Extraction

Make sure you have the required libraries installed:
!pip install yake
!pip install gensim
!pip install keybert
!pip install nltk

Keyword Extraction Methods:
TextRank
TF-IDF
RAKE
YAKE
KeyBERT

TextRank:
TextRank is an algorithm based on the PageRank algorithm, which is used by Google for ranking web pages. In the context of keyword extraction, TextRank treats words as nodes in a graph, and the edges between them represent co-occurrence relationships.
The algorithm assigns importance scores to each word based on the graph structure, and keywords are then extracted based on these scores.

TF-IDF (Term Frequency-Inverse Document Frequency):
TF-IDF is a statistical measure that evaluates the importance of a word in a document relative to a collection of documents (corpus).
It calculates a numerical value for each word based on its frequency in the document (term frequency) and its rarity across the entire corpus (inverse document frequency).
Keywords with high TF-IDF scores are considered more important.

RAKE (Rapid Automatic Keyword Extraction):
RAKE is a keyword extraction algorithm that focuses on identifying keywords by analyzing word co-occurrence and the frequency of words in a document.
It uses heuristics to identify candidate keywords and then scores them based on the frequency of occurrence and word degree in the document.

YAKE (Yet Another Keyword Extractor):
YAKE is a keyword extraction algorithm that combines aspects of both statistical and linguistic approaches.
It relies on a supervised machine learning model trained on a large dataset to identify and score candidate keywords.
YAKE considers both the frequency and the context of words in the document.

KeyBERT:
KeyBERT is a keyword extraction library that utilizes BERT embeddings, a type of pre-trained transformer model, to represent words and phrases.
It uses these embeddings to measure the similarity between words and extracts keywords by ranking them based on their similarity to the input document.
KeyBERT leverages contextual information to capture the meaning of words in the document.

Evaluation:
Calculates the F1 score for each keyword extraction method compared to reference keywords. 
Top 10 Keywords extraction.

Deployment 
Run py file

