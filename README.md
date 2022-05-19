# 255-Team-13

## Contributors
* [Shreya Hunur](https://github.com/shreyahunur) <br/>
* [Rohit Yadav](https://github.com/Rohitky34) <br/>
* [Hashmitha Katta](https://github.com/hashmithakatta) <br/>

## Spam Classifier 
![image](https://user-images.githubusercontent.com/64269342/164372641-e1073755-48de-481c-823d-643dd9bfdb11.png)

## Abstract 

Because of its global accessibility, relatively quick message transfer, and low sending cost, SMS is one of the most popular and widely used modes of communication. With technological advancements and an increase in content-based advertising, the use of Short Message Service (SMS) on phones has increased to the point where devices are occasionally flooded with many spams SMS. Spam is a term that is commonly used to describe junk or unsolicited messages or information. As a result, a spam SMS is any junk message delivered to a mobile device via text messaging. The danger is the same whether the spam is sent via email or SMS. Spam may result in the disclosure of personal information, invasion of privacy, or unauthorized access to mobile device data.

Most Internet users openly despise spam, but enough of them respond to commercial offers that spam remains a viable source of income for spammers. While most users want to do the right thing to avoid and eliminate spam, they require clear and simple guidelines on how to behave. Despite all the measures taken to eliminate spam, it has not been completely eradicated. Furthermore, if the countermeasures are overly sensitive, even legitimate SMS will be deleted.



## Problem Statement 

Because of the rapid advancement of technology used by spammers, there is a need for classifiers that are more efficient, generic, and highly adaptive. Machine learning for spam classification is a critical area of study. 

The proposed work investigates and identifies the use of various learning algorithms for classifying spam messages from SMS. The algorithm used here is a machine learning classification algorithm, which is implemented here and can be used to distinguish between spam and ham messages using the SMS spam collection data set provided. We train the machine by providing that data set so that it can learn from it and draw conclusions on its own. It is now critical to identify spam messages to reduce the number of frauds occurring around the world.

## Where to start 

### Installation
Installation of below packages required before running the project

`pip install -r requirements.txt`

### Steps to run the project
Create a folder in local for Above Git Repo and open in termianl to execute below commands-

`$ git clone https://github.com/shreyahunur/255-Team-13.git`

Navigate to folder data visualization and run DataVisualization_BeforeDataCleaning.ipynb in jupyter notebook

Navigate to folder data preprocessing and run SpamClassifierPreprocessing.ipynb in jupyter notebook

Navigate to folder data visualization and run Data_visualization_after_cleaning.ipynb in jupyter notebook

Navigate to folder Model and run SpamClassifier.ipynb in jupyter notebook


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

## Data Science Life Cycle

<img width="491" alt="Datasciencelifecycle" src="https://user-images.githubusercontent.com/56205828/166523042-1c5a0d53-fba8-4c5b-ac7d-6e4efc209fdc.png">



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
