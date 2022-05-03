Title  | Date | Author 
------------- | ------------- | -------------
Spam Classifier  | May 2022 | Shreya Hunur, San José State University
Spam Classifier  | May 2022 | Rohit Yadav, San José State University
Spam Classifier  | May 2022 | Hashmitha Katta, San José State University


# Abstract

Because of its global accessibility, relatively quick message transfer, and low sending cost, SMS is one of the most popular and widely used modes of communication. With technological advancements and an increase in content-based advertising, the use of Short Message Service (SMS) on phones has increased to the point where devices are occasionally flooded with many spams SMS. Spam is a term that is commonly used to describe junk or unsolicited messages or information. As a result, a spam SMS is any junk message delivered to a mobile device via text messaging. The danger is the same whether the spam is sent via email or SMS. Spam may result in the disclosure of personal information, invasion of privacy, or unauthorized access to mobile device data.

Most Internet users openly despise spam, but enough of them respond to commercial offers that spam remains a viable source of income for spammers. While most users want to do the right thing to avoid and eliminate spam, they require clear and simple guidelines on how to behave. Despite all the measures taken to eliminate spam, it has not been completely eradicated. Furthermore, if the countermeasures are overly sensitive, even legitimate SMS will be deleted.

# Introduction



# Methods

We have collected a dataset with messages containing both SPAM and HAM(legitimate) messages.

Methods which we will be using include:

## 1. Pre-Processing
### a. Tokenization : 
Tokenization is breaking the raw text into small chunks. Tokenization breaks the raw text into words, sentences called tokens. These tokens help in understanding the context or developing the model for the NLP. The tokenization helps in interpreting the meaning of the text by analyzing the sequence of the words.
### b. Removing unnecessary punctuation, tags
### c. Removing stop words :
Stop words are a set of commonly used words in a language. Examples of stop words in English are “a”, “the”, “is”, “are” and etc. Stop words are commonly used in Text Mining and Natural Language Processing (NLP) to eliminate words that are so commonly used that they carry very little useful information.
### d. Stemming and Lemmatization
The goal of both stemming and lemmatization is to reduce inflectional forms and sometimes derivationally related forms of a word to a common base form.
However, the two words differ in their flavor. Stemming usually refers to a crude heuristic process that chops off the ends of words in the hope of achieving this goal correctly most of the time, and often includes the removal of derivational affixes. Lemmatization usually refers to doing things properly with the use of a vocabulary and morphological analysis of words, normally aiming to remove inflectional endings only and to return the base or dictionary form of a word, which is known as the lemma .
### e. Bag of Words
A bag-of-words is a representation of text that describes the occurrence of words within a document. It involves two things: A vocabulary of known words. A measure of the presence of known words.
### f. TF-IDF
TF-IDF stands for “Term Frequency — Inverse Document Frequency”. This is a technique to quantify words in a set of documents. We generally compute a score for each word to signify its importance in the document and corpus. This method is a widely used technique in Information Retrieval and Text Mining.

TF-IDF = Term Frequency (TF) * Inverse Document Frequency (IDF)

Terminology

t — term (word)

d — document (set of words)

N — count of corpus

corpus — the total document set

## 2. Model Building:
- Build a model from vectors obtained from TFIDF
- Split dataset into train and test data
- Train model using train data
- Validate model using test data
- Calculate performance metrics

# Comparisons
Use different classifiers to classify whether SMS is spam or not
Models we will train and compare :

* Naive Bayes
* KNN
* Logistic Regression
* Support Vector Machines
* Decision Trees
* Random Forest Classifier

# Example Analysis

# Conclusions


# References
