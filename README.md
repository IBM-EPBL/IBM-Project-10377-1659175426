# IBM-Project-10377-1659175426

![image1](https://user-images.githubusercontent.com/79015800/192942989-db4d588d-18c6-4b41-9bc2-b1a5c2811c83.jpeg)

## Web Phishing Detection

TEAM ID: PNT2022TMID4768

Team Size       : 4

Team Lead       : THILLAI RAJ S

TEAM MEMBER 1   : ABISHEK B

TEAM MEMBER 2   : MAHESWARAN P

TEAM MEMBER 3   : MOHAMED NAJITH J



>### Description :dart:
>There are a number of users who purchase products online and make payments through e-banking. There are e-banking websites that ask users to provide sensitive data such as username, password & credit card details, etc., often for malicious reasons. This type of e-banking website is known as a phishing website. Web service is one of the key communications software services for the Internet. Web phishing is one of many security threats to web services on the Internet.

## Objective

A phishing website is a common social engineering method that mimics trustful uniform resource locators (URLs) and webpages. The objective of this project is to train machine learning models on the dataset given to predict phishing websites. Both phishing and benign URLs of websites are gathered to form a dataset and from them required URL and website content-based features are extracted. The performance level of each model is measured and compared.

>### Common threats of web phishing: 	:loudspeaker:
>Web phishing aims to steal private information, such as usernames, passwords, and credit card details, by way of impersonating a
>- legitimate entity.
>- It will lead to information disclosure and property damage.
>- Large organizations may get trapped in different kinds of scams.
>- Financial loss


## Models & Training

Before stating the ML model training, the data is split into 80-20 i.e., 8844 training samples & 2211 testing samples. From the dataset, it is clear that this is a supervised machine learning task. There are two major types of supervised machine learning problems, called classification and regression.

This data set comes under classification problem, as the input URL is classified as phishing (1) or legitimate (0). The supervised machine learning models (classification) considered to train the dataset in this project are:

- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machines

## End Results

From the obtained results of the above models, XGBoost Classifier has highest model performance of 92.3%. So the model is saved to the file [XGBoostClassifier.pickle.dat]
