Title  | Date | Author 
------------- | ------------- | -------------
Spam Classifier  | May 2022 | Shreya Hunur, San José State University
Spam Classifier  | May 2022 | Rohit Yadav, San José State University
Spam Classifier  | May 2022 | Hashmitha Katta, San José State University


# Abstract

Because of its global accessibility, relatively quick message transfer, and low sending cost, SMS is one of the most popular and widely used modes of communication. With technological advancements and an increase in content-based advertising, the use of Short Message Service (SMS) on phones has increased to the point where devices are occasionally flooded with many spams SMS. Spam is a term that is commonly used to describe junk or unsolicited messages or information. As a result, a spam SMS is any junk message delivered to a mobile device via text messaging. The danger is the same whether the spam is sent via email or SMS. Spam may result in the disclosure of personal information, invasion of privacy, or unauthorized access to mobile device data.

Most Internet users openly despise spam, but enough of them respond to commercial offers that spam remains a viable source of income for spammers. While most users want to do the right thing to avoid and eliminate spam, they require clear and simple guidelines on how to behave. Despite all the measures taken to eliminate spam, it has not been completely eradicated. Furthermore, if the countermeasures are overly sensitive, even legitimate SMS will be deleted.

# Introduction

Users now have personal and confidential information such as contact lists, credit card numbers, photographs, passwords, and much more stored in their smartphones, making them vulnerable to cyber-attacks via spam SMS. This allows hackers engaged in unethical activities to access smartphone data without the end-knowledge, user's jeopardizing the user's privacy. This could result in both monetary and functional losses. Spam messages appear to be on the rise, causing not only annoyance but also critical data loss for some users. Aside from that, SMS spam can be a driving force for malware and keyloggers.


The widespread distribution of this type of problem, as well as less effective security control measures, has inspired many researchers to develop a set of techniques to assist simple formula, giving them an advantage over other techniques in particular sense. We intend to compare various classifying techniques on various datasets gathered from previous research works and evaluate them based on their accuracies, precision, recall, and CAP Curve. A comparison of traditional machine learning techniques and deep learning methods will be carried out.




# Methods

We have collected a dataset with messages containing both SPAM and HAM(legitimate) messages.

Methods which we will be using include:

## 1. Pre-Processing
### a. Data Cleaning : 
Data cleaning is very crucial process in NLP. In this only alphabetic characters are extracted from text removing the punctuation and numbers, and then all characters are  converted into lowercase. This cleaned text will be then used in further processing.
### b. Tokenization : 
Tokenization is breaking the raw text into small chunks. Tokenization breaks the raw text into words, sentences called tokens. These tokens help in understanding the context or developing the model for the NLP. The tokenization helps in interpreting the meaning of the text by analyzing the sequence of the words.
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
This article discusses spam filtering techniques based on machine learning algorithms. For our experiments, we used a UCI dataset. Only this dataset was used to test our model.
Bag of Words, Count vectorizer and TF-IDF are three distinct word embedding approaches that we used. In terms of accuracy score, TF-IDF with Random Forest classification method surpasses other algorithms in the trial. However, because the dataset is unbalanced, it is not enough to judge the performance just on accuracy; the precision, recall, ROC score and f1-score of the methods must also be considered. After further testing, the RF algorithm still manages to deliver good precision and f1-score, with precision of 0.97, ROC score of 0.99 and f1-score of 0.99 . Based on the characteristics employed, different algorithms will provide different performances and results. Adding extra characteristics may aid classifiers in improving training data and performance. We'll test our model on a variety of datasets in the future.


# References
1. D. K. Renuka, T. Hamsapriya, M. R. Chakkaravarthi and P. L. Surya, "Spam Classification Based on Supervised Learning Using Machine Learning Techniques," 2011 International Conference on Process Automation, Control and Computing, 2011, pp. 1-7.
2. Shrawan Kumar Trivedi, “A Study of Machine Learning Classifiers for Spam Detection”, 2016 4th International Symposium on Computational and Business Intelligence,2016
3. Naeem Ahmed, Rashid Amin, Hamza Aldabbas, Deepika Koundal, Bader Alouffi, and Tariq Shah “Machine Learning Techniques for Spam Detection in Email and IoT Platforms: Analysis and Research Challenges”, 3 February 2022 Hindawi Security and Communication Networks Volume, 2022
4. Mehul Gupta, Aditya Bakliwal, Shubhangi Agarwal & Pulkit Mehndiratta , “A Comparative Study of Spam SMS Detection using Machine Learning Classifiers”, Proceedings of 2018 Eleventh International Conference on Contemporary Computing (IC3), 2018
5. https://towardsdatascience.com/your-guide-to-natural-language-processing-nlp-48ea2511f6e1

