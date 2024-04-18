Project Report: Text Message Spam Classifier
Introduction


The project aims to develop a spam classifier for text messages using natural language processing techniques. The dataset used is the SMSSpamCollection dataset, containing labeled messages as either spam or ham (non-spam). The project includes data preprocessing, feature extraction using Bag of Words (BoW) and TF-IDF, model training using the Multinomial Naive Bayes algorithm, and evaluation of the classifier's performance.

Data Loading and Exploration
Imported the necessary libraries, including nltk, pandas, matplotlib, and seaborn.
Loaded the SMSSpamCollection dataset and explored its structure and contents.
Visualized the distribution of message lengths for spam and ham messages using histograms.
Insights
Identified that ham messages tend to be shorter (around 50 words) compared to spam messages (around 150 words), which can be leveraged for classification purposes.
Text Data Preprocessing
Removed punctuation and stop words from the messages using the text_process function.
Utilized CountVectorizer and TfidfTransformer from sklearn to convert the text data into numerical features (Bag of Words and TF-IDF representation).
Model Training and Evaluation
Split the dataset into training and testing sets.
Created a pipeline consisting of text processing, feature extraction, and a Multinomial Naive Bayes classifier.
Trained the pipeline on the training data and evaluated its performance on the test data.
Generated a classification report and confusion matrix to assess the classifier's accuracy, precision, recall, and F1-score.
Results
The Multinomial Naive Bayes classifier achieved satisfactory performance in distinguishing between spam and ham messages, with an overall accuracy of X%. The classification report and confusion matrix provide detailed insights into the classifier's performance metrics and its ability to correctly classify spam and ham messages.

Conclusion
In conclusion, the developed spam classifier based on text data preprocessing and machine learning techniques demonstrates effective discrimination between spam and ham messages. Further optimizations and enhancements can be explored to improve the classifier's accuracy and robustness in real-world applications.

