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

   
## Dependencies/Imports:
###  `nltk`
###  `random`
###  `movie_reviews` from `nltk.corpus`
###  `~~SklearnClassifier from nltk.classify.scikitlearn~~`
###  `pickle`
## FROM `sklearn.naive_bayes`:
###  `MultinomialNB`, `BernoulliNB`
## FROM `sklearn.linear_model`:
###  `LogisticRegression`, `SGDClassifier`
## FROM `sklearn.svm`:
###  `SVC`, `LinearSVC`, `NuSVC`