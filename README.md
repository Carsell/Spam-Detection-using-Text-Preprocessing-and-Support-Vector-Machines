Email Spam Detection
Overview
This Python script focuses on email spam detection using natural language processing techniques. The process involves data cleaning, lemmatization, and TF-IDF feature extraction. A Support Vector Machine (SVM) classifier is trained to distinguish between spam and non-spam emails.

Steps
1. Data Cleaning
Ensure data quality by handling missing values. The dataset is loaded from "spam_or_not_spam.csv."

2. Text Preprocessing
Implement lemmatization to enhance the accuracy of the model. The lemmatize_text function processes the 'email' column.

3. Sentiment Analysis
Assign sentiment labels to each text. (Note: Sentiment analysis is not implemented in the original code.)

4. Model Creation and Evaluation
Split the dataset into training and testing sets. Utilize TF-IDF vectorization to extract features. Train a Support Vector Machine (SVM) classifier and evaluate its performance using the classification report.

Usage
Ensure you have the required libraries installed: pandas, nltk, scikit-learn.
Run the script, providing the path to your dataset.
Feel free to adapt and enhance the code to suit your specific requirements. Contributions are welcome!
