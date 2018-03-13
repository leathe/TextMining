## Classifiers:

### NB_classifier
   Naive Bayes Classifier (NLTK)
### MNB_classifier
   Multinomial Naive Bayes Classifier (Scikit learn)
### BNB_classifier
   Bernoulli Naive Bayes Classifier (Scikit learn)
### LogisticRegression_classifier
   Logistic Regression Classifier (Scikit learn)
### SGDClassifier_classifier 
   Stochastic Gradient Descent Classifier(Scikit learn)
### SVC_classifier
   Support Vector Classifier (Scikit learn)
   Will not be used. Returns a very poor accuracy percentage.
### LinearSVC_classifier
   Linear Support Vector Classifier (Scikit learn)
### NuSVC_classifier
   Nu Support Vector Classifier (Scikit learn)

## Folders:
   SavedTrainingData folder contains pre-trained training data for each classifier.

   
### Dependencies/Imports:
####  `nltk`
####  `random`
####  ~~`SklearnClassifier from nltk.classify.scikitlearn`~~
####  `pickle`
###  from`nltk.corpus`:
#### `movie_reviews`
### from `sklearn.naive_bayes`:
####  `MultinomialNB`, `BernoulliNB`
### from `sklearn.linear_model`:
####  `LogisticRegression`, `SGDClassifier`
### from `sklearn.svm`:
####  `SVC`, `LinearSVC`, `NuSVC`