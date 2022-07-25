# About
The Project is to find secure and malcious websites using machine learning which also coverrs NLP. Moreover we use count vectorizes and TfIf vectorizer, here count vectorizer refers to the variable n a sentence and TfIf vectorization is ratio of Tf and If. It creates a dictionary based on unique words and assigned with frequency. In this project during the data preprocessing we commonl split '.','/',':' and remaning are neccesary for url to determine the url safety.
# Pre-requisites:
1)dataset
2)Pandas
3)Count vectorizer
4)TfidF vectorizer
5)python

Many algoritms are time consuming as dataset containg lakhs of urls.
Phishing:
    Phising is a tool used to install malware to any other device, hacking while these commonly look like similar famous webites but differ in domain and subdomain or there might be an addition specific characters.
#Algoritms:
 # 1) Count Vectorization:
           This algorithmn is part of sklearn in feature extraction used to 
           tokenize based on the frequency of the word in a sentence.
           For eg: In the sentence "Hi Gmrit,Gmrit is in Razam. 
           Here Gmr is repeated 2 times and Razam is repeated 1 time and stop words are removed.
# 2) TfIdf Vectorization:
            This algorithmn is part of sklearn in feature extraction similar 
            to Count vectorization but the only differnce is that we use Tf/If 
            ratio inn place count or frequency of word in a sentence.
 
 #  Classifiers:
  As the data given is very huge it takes more time for training and fitting while there are few algoritmns which are used that gives good accuracy and executes fast.
  1) Logistic Regression
  2) SVC
  3) Random forest with n_estimators less than 20
  4) Decision tree
  5) Naive based
  
  Few algoritms takes lot of time like:
  1) adabooster
  2) GuassianNB
  3) Random forest with n_estimators =100 takes lots of time
  
  In case if we find modele not found we need to intall using pip
   # pip install sklearn
  To make use of it
  1) from sklearn.feature_extraction.text import CountVectorizer
  2) from sklearn.feature_extraction.text import TfidfVectorizer
