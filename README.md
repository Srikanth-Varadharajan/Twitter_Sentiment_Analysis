<h1># Twitter_Sentiment_Analysis</h1> <br/>
<ol>
<li>Importing necessary libraries:</li><br/>
<li>pandas: Used for data manipulation and analysis.</li><br/>
<li>re: Regular expression library for text processing.</li><br/>
<li>nltk: Natural Language Toolkit for natural language processing tasks.</li><br/>
<li>matplotlib.pyplot: Plotting library for creating visualizations.</li><br/>
<li>train_test_split: Function from scikit-learn for splitting data into training and testing sets.</li><br/>
<li>TfidfVectorizer: Term Frequency-Inverse Document Frequency vectorizer from scikit-learn for converting a collection of raw documents to a matrix of TF-IDF features.</li><br/>
<li>LogisticRegression: Logistic Regression classifier from scikit-learn.</li><br/>
<li>Reading the CSV file into a DataFrame: The code reads a CSV file containing Twitter data using Pandas.</li><br/>
<li>Data Exploration: The code prints the shape and information about the DataFrame, as well as the count of null values in each column.</li><br/>
<li>Data Cleaning: Columns 'ids', 'date', 'flags', and 'user' are dropped from the DataFrame.</li><br/>
<li>Text Cleaning: A function clear_text is defined to perform various text cleaning operations on the 'comments' column.</li><br/>
<li>Text Preprocessing: Stop words are removed, and the text is converted to lowercase using NLTK. The result is stored in the 'comments' column.</li><br/>
<li>Target Variable Transformation: The 'target' column is transformed into a new column 'final_target' with values 0, 1, or 2.</li><br/>
<li>Histogram Visualization: A histogram of the 'final_target' column is plotted using Matplotlib or seaborn.</li><br/>
<li>Train-Test Split: The data is split into training and testing sets.</li><br/>
<li>Model Training: A TfidfVectorizer and Logistic Regression classifier are combined into a pipeline, which is then fitted to the training data.</li><br/>
<li>Model Evaluation: Confusion matrix and various metrics (accuracy, precision, recall) are calculated and printed.</li><br/>
<li>Making Predictions: A sample input 'Good' is used to make a prediction using the trained model.</li><br/>
</ol>
