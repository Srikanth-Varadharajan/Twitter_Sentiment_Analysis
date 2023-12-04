# Twitter_Sentiment_Analysis\n
Importing necessary libraries:\n
pandas: Used for data manipulation and analysis.\n
re: Regular expression library for text processing.\n
nltk: Natural Language Toolkit for natural language processing tasks.\n
matplotlib.pyplot: Plotting library for creating visualizations.\n
train_test_split: Function from scikit-learn for splitting data into training and testing sets.\n
TfidfVectorizer: Term Frequency-Inverse Document Frequency vectorizer from scikit-learn for converting a collection of raw documents to a matrix of TF-IDF features.\n
LogisticRegression: Logistic Regression classifier from scikit-learn.\n
Reading the CSV file into a DataFrame: The code reads a CSV file containing Twitter data using Pandas.\n
Data Exploration: The code prints the shape and information about the DataFrame, as well as the count of null values in each column.\n
Data Cleaning: Columns 'ids', 'date', 'flags', and 'user' are dropped from the DataFrame.\n
Text Cleaning: A function clear_text is defined to perform various text cleaning operations on the 'comments' column.\n
Text Preprocessing: Stop words are removed, and the text is converted to lowercase using NLTK. The result is stored in the 'comments' column.\n
Target Variable Transformation: The 'target' column is transformed into a new column 'final_target' with values 0, 1, or 2.\n
Histogram Visualization: A histogram of the 'final_target' column is plotted using Matplotlib or seaborn.\n
Train-Test Split: The data is split into training and testing sets.\n
Model Training: A TfidfVectorizer and Logistic Regression classifier are combined into a pipeline, which is then fitted to the training data.\n
Model Evaluation: Confusion matrix and various metrics (accuracy, precision, recall) are calculated and printed.\n
Making Predictions: A sample input 'Good' is used to make a prediction using the trained model.\n
