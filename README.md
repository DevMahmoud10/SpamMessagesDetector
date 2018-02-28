# Spam Messages Detector
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Spam Messages Detector](#spamMessagesDetector)
	- [Explanation](#explanation)
	- [Objective](#objective)
	- [Setup](#setup)
		- [Pandas](#pandas)
        - [Scikit-learn](#scikit-learn)
        - [Matplot](#matplot)

	- [Data](#data)
	- [Methodologies](#methodologies)
	- [Results](#results)

<!-- /TOC -->
## Explanation
More Messages delivered to us with Ads that be noisy and need to be detected, [Kaggle.com Problem ](https://www.kaggle.com/uciml/sms-spam-collection-dataset) need to build a prediction model that will accurately classify which texts are spam.

## Objective
Building a spam messages detector that would be able to classify spam messages from another messages.

## Setup
- ### pandas
```
pip install pandas
```
- ### scikit-learn
```
pip install -U scikit-learn
```
- ### matplot
```
python3 -mpip install matplotlib
```

## Data
- Public set of SMS labeled messages that have been collected for mobile phone spam research about (~5000 message)

	 
## Methodologies
- TF-IDF vectorizer to transform messages into numerical data.
- Logistic Regression classification algorithm.

## Results
F1-Score : 97.63%

