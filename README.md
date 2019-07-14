# Spam email detection model

* This model offers a possibility to detect whether a email is spam or not. Data was taken from http://spamassassin.apache.org/old/publiccorpus/.
* Folder named "Train" contains training data, forlder named "Test" contains test data.
* In Train and Test, there are two folders contain non-spam email and sapm email. 

# 1.Configuration Instruction
* 1.1 Install Library
	* Open jupyter notebook and type "!pip install ipynb".
# 2.Installation Instructions
	* After training by  run file Model.ipynb, it will save your model into a file named 'model'.
	* Try your own email by take palce Noe by the path to your own email in TryYourOwnEmail.py.ipynb
# 3.List file are contained in program:
	* Model.ipynb: Training and choose the best hyperparameter of  model after preprocessing data.
	* Training_data.ipynb: return X_train, y_train
	* TryyourOwnEmail: Try model with your own email.
	* createVocab.ipynb: create n-length vocabulary list based on the frequency of each word appear in spam email.
	* emailFeatures.ipynb: return a vector in R^n.
	* getVocabList.ipynb: get vocabulary list

** Star if you like:)

