# 📰 Fake News Detection — NLP Assignments

A collection of Natural Language Processing (NLP) assignments focused on text processing, analysis, and fake news detection concepts.

##  Project Overview

This project contains hands-on NLP assignments that cover fundamental text processing techniques used in fake news detection pipelines. The notebooks demonstrate progressively advanced NLP concepts from basic string manipulation to machine learning-based text representations.

##  Repository Structure

```
Fake_news_detection/
├── README.md                              # This file
├── .gitignore                             # Git ignore rules
├── NLP_Word_Count .ipynb                  # Lecture notebook: Word counting techniques
├── _4_Frequency_Distribution.ipynb        # Lecture notebook: Frequency distribution analysis
├── assignment1_fake_news_detection.ipynb   # Assignment 1: 15 solved NLP problems
├── Assignment2_FND.ipynb                  # Assignment 2: 15 solved NLP problems
└── Fake News Detection (1).pdf            # Assignment reference document
```

## Assignment 1 — Topics Covered

| # | Problem | Concepts |
|---|---------|----------|
| 1 | Word Count (No Punctuation) | Python built-in string methods |
| 2 | URL Extraction | Regular Expressions (regex) |
| 3 | Tokenization & Lowercasing | NLTK `word_tokenize` |
| 4 | Stemming | NLTK `PorterStemmer` |
| 5 | Lemmatization | spaCy lemmatization |
| 6 | POS Tagging | spaCy Part-of-Speech tagging |
| 7 | Named Entity Recognition | spaCy NER |
| 8 | Top N Common Words | `collections.Counter` |
| 9 | Stop Word Removal | Custom stop word filtering |
| 10 | Character Frequency | `collections.Counter` |
| 11 | Text Cleaning | Regex (remove digits, extra spaces) |
| 12 | Average Sentence Length | NLTK `sent_tokenize` + `word_tokenize` |
| 13 | Enhanced Sentiment Analysis | Rule-based with Mixed Sentiment |
| 14 | Bag-of-Words | scikit-learn `CountVectorizer` |
| 15 | TF-IDF Keywords | scikit-learn `TfidfVectorizer` |

## Assignment 2 — Topics Covered

| # | Problem | Concepts |
|---|---------|----------|
| 1 | Basic Tokenization | NLTK & spaCy Tokenization |
| 2 | Stop Word Removal | NLTK Stopwords |
| 3 | Stemming vs Lemmatization | `PorterStemmer` & `WordNetLemmatizer` |
| 4 | Text Classification | `CountVectorizer` & `LogisticRegression` |
| 5 | POS Tagging | spaCy Part-of-Speech tagging |
| 6 | Named Entity Recognition | spaCy NER |
| 7 | RegEx Pattern Extraction | `re` (Email and Phone numbers) |
| 8 | Generating N-Grams | NLTK `ngrams` (bigrams, trigrams) |
| 9 | Rule-Based Sentiment Analysis | VADER `SentimentIntensityAnalyzer` |
| 10| Sentence Similarity | spaCy word vectors similarity |
| 11| Document Clustering | `TfidfVectorizer` & `KMeans` |
| 12| Basic Text Summarization | `sumy` `LuhnSummarizer` |
| 13| Rule-Based ABSA | Aspect-Based Sentiment Analysis |
| 14| Data Augmentation | Synonym Replacement |
| 15| Frequency-Based Keyword Extraction | NLTK `FreqDist` |

##  Technologies & Libraries

- **Python 3.x**
- **NLTK** — Tokenization, stemming, sentence splitting
- **spaCy** — Lemmatization, POS tagging, NER
- **scikit-learn** — CountVectorizer, TfidfVectorizer
- **regex (re)** — Pattern matching and text cleaning
- **collections** — Counter for frequency analysis
- **sumy** — Text summarization


## 👤 Author

- **Harshit Pandey** — [GitHub Profile](https://github.com/harshitpandey-7)
