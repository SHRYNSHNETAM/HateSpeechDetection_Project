#Hate Speech Detection using Machine Learning
This project aims to detect hate speech and offensive language in tweets using machine learning algorithms. The dataset used for this project is "Hate Speech and Offensive Language Dataset" from the University of Victoria.

##Requirements
Python 3.x
nltk
numpy
pandas
matplotlib
scikit-learn
seaborn
wordcloud

##Installation
Clone the repository
Install the required packages by running pip install -r requirements.txt
Run the Jupyter Notebook Hate Speech Detection.ipynb to see the implementation 

##Dataset
The dataset used in this project contains three columns: "class", "tweet", and "count". The "class" column indicates whether a tweet is "Hate", "Offensive", or "None". The "tweet" column contains the text of the tweet, and the "count" column contains the number of times a tweet was labeled as "Hate" or "Offensive".

##Implementation
The project implementation is done in Jupyter Notebook Hate Speech Detection.ipynb.

1.The dataset is loaded using pandas library and preprocessing is done using nltk library.
2.The processed data is split into training and testing sets.
3.Machine learning models such as Decision Tree, K-Nearest Neighbor, Logistic Regression, Naive Bayes, and Random Forest are trained on the training set.
4.The trained models are tested on the testing set.
5.The accuracy scores and confusion matrices are calculated for each model.

##Results
The accuracy scores for each model are as follows:

Random Forest Accuracy: 0.8785555779705467
Logistic Regression Accuracy: 0.9039741779301997
Decision Tree Accuracy: 0.8777486382892878
Naive Bayes Accuracy: 0.3147064756909421
KNN Accuracy: 0.8317530764575348
The results show that Logistic Regression has the highest accuracy score among all the models.

##Conclusion
The project successfully detects hate speech and offensive language in tweets using machine learning algorithms. The results show that Logistic Regression has the highest accuracy score among all the models. The project can be further improved by using deep learning models or more advanced techniques for text preprocessing.
