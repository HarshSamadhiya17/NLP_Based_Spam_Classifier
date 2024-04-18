<h1>Project Report: Text Message Spam Classifier</h1>
<h2>Introduction</h2>
<p>
The project aims to develop a spam classifier for text messages using natural language processing techniques. The dataset used is the SMSSpamCollection dataset, containing labeled messages as either spam or ham (non-spam). The project includes data preprocessing, feature extraction using Bag of Words (BoW) and TF-IDF, model training using the Multinomial Naive Bayes algorithm, and evaluation of the classifier's performance.
</p>

<h2>Data Loading and Exploration</h2>
<ul>
<li>Imported the necessary libraries, including nltk, pandas, matplotlib, and seaborn.
<li>Loaded the SMSSpamCollection dataset and explored its structure and contents.</li>
<li>Visualized the distribution of message lengths for spam and ham messages using histograms.
Insights</li>
<li>Identified that ham messages tend to be shorter (around 50 words) compared to spam messages (around 150 words), which can be leveraged for classification purposes.</li>
</ul>
<h2>Text Data Preprocessing</h2>
<ul>
<li>Removed punctuation and stop words from the messages using the text_process function.</li>
<li>Utilized CountVectorizer and TfidfTransformer from sklearn to convert the text data into numerical features (Bag of Words and TF-IDF representation).</li>
</ul>
<h2>Model Training and Evaluation<h2>
<ul>
<li>Split the dataset into training and testing sets.</li>
<li>Created a pipeline consisting of text processing, feature extraction, and a Multinomial Naive Bayes classifier.</li>
<li>Trained the pipeline on the training data and evaluated its performance on the test data.</li>
<li>Generated a classification report and confusion matrix to assess the classifier's accuracy, precision, recall, and F1-score.</li>
Results</li>
<li>The Multinomial Naive Bayes classifier achieved satisfactory performance in distinguishing between spam and ham messages, with an overall accuracy of 96%. The classification report and confusion matrix provide detailed insights into the classifier's performance metrics and its ability to correctly classify spam and ham messages.</li>
</ul>
<h2>Conclusion</h2>
<p>In conclusion, the developed spam classifier based on text data preprocessing and machine learning techniques demonstrates effective discrimination between spam and ham messages. Further optimizations and enhancements can be explored to improve the classifier's accuracy and robustness in real-world applications.
</p>
