# 255-Team-13

## Contributors
* [Shreya Hunur](https://github.com/shreyahunur) <br/>
* [Rohit Yadav](https://github.com/Rohitky34) <br/>
* [Hashmitha Katta](https://github.com/hashmithakatta) <br/>

## Spam Classifier 
![image](https://user-images.githubusercontent.com/64269342/164372641-e1073755-48de-481c-823d-643dd9bfdb11.png)

## Abstract 

Because of its global accessibility, relatively quick message transfer, and low sending cost, e-mail is one of the most popular and widely used modes of communication. Flaws in e-mail protocols, as well as an increase in electronic business and financial transactions, all contribute to an increase in e-mail-based threats. Email spam is one of the most serious issues facing today's Internet, causing financial harm to businesses and annoyance to individual users. Spam emails are invading users' mailboxes without their knowledge. They use more network capacity and time checking and deleting spam emails.

Most Internet users openly despise spam, but enough of them respond to commercial offers that spam remains a viable source of income for spammers. While most users want to do the right thing to avoid and eliminate spam, they require clear and simple guidelines on how to behave. Despite all the measures taken to eliminate spam, it has not been completely eradicated. Furthermore, if the countermeasures are overly sensitive, even legitimate emails will be deleted.

Among the methods developed to combat spam, filtering is one of the most important. Many spam filtering studies have focused on more sophisticated classifier-related issues.

## Problem Statement 

Because of the rapid advancement of technology used by spammers, there is a need for classifiers that are more efficient, generic, and highly adaptive.
Machine learning for spam classification is a critical area of study. The proposed work investigates and identifies the use of various learning algorithms for classifying spam messages from e-mail.

Several attempts have been made to detect and filter spam email on the client side in order to solve the spam problem.


## Dataset

Dataset : https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

The UCI Machine Learning Repository has datasets for machine learning techniques. The SMS Spam Collection (hereafter the corpus) is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam. 

The files contain one message per line. Each line is composed by two columns: one with label (ham or spam) and other with the raw text. Here are some examples:

ham   What you doing?how are you?
ham   Ok lar... Joking wif u oni...
ham   Cos i was out shopping wif darren jus now n i called him 2 ask wat present he wan lor. Then he started guessing who i was wif n he finally guessed darren lor.
spam   FreeMsg: Txt: CALL to No: 86888 & claim your reward of 3 hours talk time to use from your phone now! ubscribe6GBP/ mnth inc 3hrs 16 stop?txtStop
spam   Sunshine Quiz! Win a super Sony DVD recorder if you canname the capital of Australia? Text MQUIZ to 82277. B
spam   URGENT! Your Mobile No 07808726822 was awarded a L2,000 Bonus 

## Methodology

We will be using supervised models, mainly different classification models like:

* Naive Bayes
* KNN
* Logistic Regression
* Support Vector Machines
* Decision Trees
* Random Forest Classifier

These classification methods will help us to classify the data into spam and not-spam, based on given features. 

## Performance Metrics 

Since it is a classification problem we will use the following performance metrics:-

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1 score
* Receiver operating characteristic(ROC) and Area under the curve(AUC)
