# Detecting-Privacy-Invasive-Bots-on-YouTube
Privacy-Invasive Bot Detection on YouTube Using Machine Learning

Description: 
YouTube is facing a major problem with several bots spamming YouTubers with random comments. One type of comment that has been commonly posted is commenting several random names or cities. These comments, although seemingly innocuous, are used to dox anonymous contect creators and/or to find their location. 

Youtube allows you to add filters to comments being posted. This allows YouTubers to add their names, address, and any other personal identifiable information to the filter to prevent them being exposed. The bots comment several hundred names and addresses (Usually cities to narrow down the address) to understand which comments were deleted. 

Purpose:
This research paper aims to detect these privacy invasive YouTube bots using machine learning models such as Bernoulli Naive Bayes and SUpport Vector Machine (SVM)

Workflow:

1. Converts text data into numerical representations using CountVectorizer.
Analyzes comment lengths, word frequencies, and class balance.
Machine Learning Models Used

2. Bernoulli Naïve Bayes – Best suited for binary classification of spam vs. non-spam comments.
Support Vector Machine (SVM) – (Optional) Can be integrated for more robust classification.
Model Training & Evaluation

3. Splits data into training and testing sets.
Evaluates performance using accuracy, precision, recall, and F1-score.
Uses a confusion matrix to understand misclassifications.
Spam Detection

3. Takes user-inputted text and predicts whether it's spam or not spam.
Helps identify bots that post automated or privacy-invasive comments.


Conclusion:
While this is a research on detecting spam bots on YouTube, there needs to be an active model in place to actually implement this methodology proactively. We believe that while this model might still be scratching the surface of practical implementation, it is a step forward on stopping this issue.
