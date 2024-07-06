# SMS-Spam-Classifier
SMS Spam Classifier

Objective
Learn how to build a spam detection or Text classification model in Python using data science techniques and your questions like How to make System which detects Spam.

Data Preparation
In the step, we load the SMS dataset which consists of messages and labels for each message belong to spam or non-spam. This (data) is further divided into training and test to check the performance.

Text Preprocessing
Before using the data to train a model, we preprocess it by cleaning text and deleting noise such as punctuation,numbers and stop words. This is very important to improve the quality of data entering into model.

Feature Extraction
For this, convert the text data to numerical features using methods like TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This way the text is shaped into type which can be given as input to machine learning models.

Model Training
Create a classification model by fitting your training data. The Multinomial Naive Bayes model works well in this case given its effectiveness with text classification tasks.

Evaluation
Run the trained model on test data to measure different scores like accuracy, precision-recall and f1-score. Once it is done, we check how well our model has performed.
