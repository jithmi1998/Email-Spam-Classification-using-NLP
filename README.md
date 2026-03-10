# Email-Spam-Classification-using-NLP

**Project Overview**
This project builds an email spam classifier using Natural Language Processing (NLP) techniques. The model classifies emails into spam and non-spam categories using TF-IDF feature extraction and the Multinomial Naive Bayes algorithm.

The goal is to automatically detect unwanted spam emails using machine learning techniques.

**Dataset** 
Spam email dataset from Kaggle:

https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset

The dataset contains email text and a binary label indicating whether the email is spam

**Tools and Libraries**
1. Python
2. Pandas
3. Matplotlib
4. NLTK
5. Scikit-learn

**Steps Performed**
1. Uploaded the spam email dataset
2. Performed data exploration and visualization to understand the dataset structure and distribution of spam and non-spam emails using Matplotlib.
3. Cleaned email text using NLP preprocessing techniques
4. Removed punctuation, numbers, and stopwords
5. Converted text into numerical features using TF-IDF vectorization
6. Split the dataset into training and testing sets
7. Trained a Multinomial Naive Bayes classifier
8. Evaluated the model using accuracy, precision, recall, and F1-score
9. Visualized results using a confusion matrix generated with Matplotlib
10. Tested the trained model using custom email example
11. Saved the trained model and TF-IDF vectorizer for future use.

**Model Performance**
1. Accuracy: 97.8%
2. Precision: 98.5%
3. Recall: 92.8%
4. F1 Score: 95.6%

**Files Included**
1. Jupyter Notebook
2. Saved model file
3. Saved vectorizer
5. Visualization graphs

**Conclusion**
The model performed very well in classifying spam emails and demonstrated that TF-IDF with Multinomial Naive Bayes is effective for spam detection tasks.
