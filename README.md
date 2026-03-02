**GOAL** - THIS IS A MOVIE RECOMMENDATION MODEL WHERE THE MODEL PREDICTS TOP 5

---

SIMIALAR MOVIES WHICH USER MAY LIKE TO WATCH SIMILAR TO ITS ENTERED MOVIE CHOICE.  
the dataset conatins details of 5000 movies taken from kaggle. we have used vectorization technique to find the similarity between movies and used some scikit learn libraries like countvectorization for converting string into vectors, nltk for stemming words , cosine_similarity to find distance between vectors . we hav used random forest and accuracy and roc-auc and confusion matrix for regression metric
**Difficulty**- main difficulty was how to decide the similarity criteria between two movies because there are lakhs of words in our feature 'tags' so answer to this was vectoriztion and cosine distance and also we took help of online documentation.
**LEARNING** - most importantly we learned about how vectorization actually works and best way to deal when we are dealing with categorical columns. we also learned about stemming methos then we learned the workflow of any ml project from preprocessing to final prediction. our data was actally very clean so no need to perform any hard EDA
