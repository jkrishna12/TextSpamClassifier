# TextSpamClassifier

This is a text corpus of over 5,500 English SMS messages with ~13% labeled as spam. The text file contains one message per line with two columns: the label ("ham" or "spam") and the raw text of the message. Messages labeled as "ham" are non-spam messages that can be considered legitimate. 

# Techniques
- Used Spacy and WordCloud to create informative visualisation for exploratory data analysis
- Preprocessed text data by lemmatising tokens and removing stopwords
- Leveraged RegEx to keep important data
- Implemented MultinomialNB and LinearSVC models from Sci-kit Learn
- Created confusion matrix and ROC curve to evaluate model performance
- Performed hyperparameter tuning with final model achieving an accuracy of 98% 
