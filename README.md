**Network Activity Anomaly Detection**

This repository contains code for building and evaluating a machine learning model to predict network activity as either normal or a "Neptune" attack based on a provided dataset.

**Dataset**
The dataset consists of detailed records of network activities, capturing various attributes associated with network connections. Each record is labeled to indicate whether the activity is normal (attack = 0) or a Neptune attack (attack = 1).

**Neptune Attack**
A Neptune attack, also known as a SYN flood attack, is a type of denial-of-service (DoS) attack where an attacker overwhelms a target system with a high number of SYN requests. This causes the system to become unresponsive to legitimate traffic by exploiting the TCP handshake process to consume resources on the target machine.

**Dataset Details**
Training Set: 86,845 rows
Test Set: 21,712 rows

**Objective**
The goal is to train a machine learning model using the training dataset to predict whether entries in the test set represent normal network activity or a Neptune attack.

**Machine Learning Model**
The model used for this prediction task is Random Forest Classifier. The model is trained on features extracted from the network activity dataset.

**Files**
train.csv: CSV file containing the training dataset.
test.csv: CSV file containing the test dataset.
**Requirements**
To run the code, you'll need Python 3 along with the following libraries:

numpy
pandas
scikit-learn
matplotlib
Seaborn
