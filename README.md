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


## Dataset

Dataset : https://www.openml.org/search?type=data&status=active&qualities.NumberOfInstances=between_1000_10000&id=44

The UCI Machine Learning Repository has datasets for machine learning techniques. UCI's spam dataset is made up of data gathered from 4601 email messages. In the Spam dataset, each instance has 58 properties. The frequency of a certain word or character in the email that corresponds to the instance is represented by the majority of the characteristics.

word freq w: 48 attributes describing the frequency of word w, the percentage of words in the email.

char freq c: 6 attributes describing the frequency of a character c, defined in the same way as word frequency.

Char freq cap: 3 attributes describing the longest length, total numbers of capital letters and average length.

spam class: the target attribute denoting whether the email was considered spam or no spam.

## 3. Description of the problem you’ll solve. 

Use the Spambase dataset from the UCI Machine Learning Repository to classify spam. This data is already parsed down from email to features.

## 4. Potential methods you will consider apply (these can change as you play with the data). Will you be doing unsupervised vs supervised methods? What specific methods within unsupervised and supervised will help you answer your questions from point #3?

We will be using supervised models, mainly different classification models like:

* Naive Bayes
* KNN
* Logistic Regression
* Support Vector Machines
* Decision Trees
* Random Forest Classifier

These classification methods will help us to classify the data into spam and not-spam, based on given features. 
