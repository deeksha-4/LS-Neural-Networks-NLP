# Week 2

Now that you've gained an insight into implementing neural networks, let's shift our focus to the main topic of this course- Natural Language Processing (NLP).

In Week 2, you will understand the basic concepts behind NLP and its applications, and implement those concepts via neural networks in this week's assignment.

This page contains links to section-wise resources on this week's topics. Please go through all of them carefully. The graded assignment for this week will be uploaded shortly.

- [Natural Language Processing (NLP)](<#natural-language-processing-(nlp)>)
  - [Word Embeddings](#word-embeddings)
  - [Text Preprocessing](#text-preprocessing)
  - [Sentiment Analysis](#sentiment-analysis)
- [Pandas Basics](#pandas-basics)
- [spaCy](#spacy)
- [Assignment](#assignment)

## Natural Language Processing (NLP)

Natural Language Processing is the AI technique by which computers are trained to recognize, understand and reply in human 'natural' languages. Refer to the following links to get a brief understanding of NLP and the concepts behind it.

- [**Short introductory video**](https://youtu.be/CMrHM8a3hqw)
- [**Advanced textbook by Dan Jurafsky**](https://web.stanford.edu/~jurafsky/slp3/), **OPTIONAL**, for those who are interested
- [**Youtube Playlist by codebasics**](https://www.youtube.com/playlist?list=PLeo1K3hjS3uuvuAXhYjV2lMEShq2UYSwX) (contains extra content)

### Word Embeddings

Neural networks cannot process words directly; they deal only with numerical vectors and their computations. In order to feed text as input to a neural network, we will first need to convert it into vector form, using word embeddings. There exist many different techniques (TF-IDF, Skip-gram, CBOW) and implementations (Glove, FastText, etc.) for this purpose.

- [**Brief conceptual overview**](https://www.geeksforgeeks.org/word-embeddings-in-nlp/)
- [**Another conceptual site**](https://towardsdatascience.com/nlp-101-word2vec-skip-gram-and-cbow-93512ee24314), specifically for skip gram models.

### Text Preprocessing

Real word text is often not in a format appropriate for analysis. Things like spelling mistakes, punctuations, tenses and more complex concepts of a language are difficult to translate into vector representations. To clean up and simplify the input data, we use several preprocessing techniques. Refer to the below link on the same.

- [**Detailed guide**](https://www.analyticsvidhya.com/blog/2021/06/text-preprocessing-in-nlp-with-python-codes/) (Recommended)
- [**Youtube Video**](https://www.youtube.com/watch?v=nxhCyeRR75Q), focusing more on post-cleanup steps like tokenization, stemming and lemmetization

### Sentiment Analysis

Sentiment analysis is a form of text classification, which is used in NLP to determine the underlying sentiments and emotions behind text. Here are some resources to get you started.

- [Short intro](https://www.geeksforgeeks.org/what-is-sentiment-analysis/)

## Pandas Basics

Pandas (Python data analysis) is a Python library frequently used to analyse datasets. You will need to use it in this week's assignment to manage and analyse the corpus. Note that you only need a basic idea of DataFrames in order to complete the assignment.

- [**w3schools tutorial**](https://www.w3schools.com/python/pandas/default.asp)
- [**Official Pandas documentation**](https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html)

## spaCy

spaCy is another Python library used to implement advanced NLP techniques. Use the following links as references for the syntax and implementation.

- [**Official documentation**](https://spacy.io/usage/spacy-101)
- [**Another tutorial**](https://realpython.com/natural-language-processing-spacy-python/)
- [**YouTube playlist- NLP using spaCy**](https://www.youtube.com/playlist?list=PLeo1K3hjS3uuvuAXhYjV2lMEShq2UYSwX), you can go through the relevant videos from here as well.

## Assignment

This week's assignment has been released. Open [**Skip_gram_in_PyTorch_(Graded).ipynb**](https://colab.research.google.com/drive/1qOcuPMjTDvs79CUWUX3g1sqn1otPe1U-?usp=sharing) in Colaboratory, and save a copy of the notebook to your own Drive. Due to issues with how some Markdown elements are rendered on GitHub, the notebook has not been added to the repo this time.

The assignment uses NLTK for some pre-processing tasks instead of spaCy, but the usage is extremely minimal and adequate clarifications on where and how it is used are included.

Submission will be taken via [**this google form**](https://forms.gle/7nty7641o3UJUGyM8)
