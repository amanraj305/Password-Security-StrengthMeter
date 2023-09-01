# ExoPassword - Password Strength Analysis
Analyze the strength of your passwords in one click!

To ensure correctness of our results, we output the strength of the password using four different Machine Learning models.

The models used are:
* Logistic Regression
* Naive Bayes
* Decision Tree
* Multi Layer Perceptron Network

## Installation
* Install requirements.txt;
```
pip install -r requirements.txt
```
Note: Create a virtual environment if you wish to:
```
virtualenv venv
```

* Run the project:
```
python app.py
```
Note: If the joblib files fail to load it might be because of version mismatch. In that case, try training the models and overwrite the joblib files.
```
python DecisionTree.py
python LogisticRegression.py
python NaiveBayes.py
python NeuralNetwork.py
```
