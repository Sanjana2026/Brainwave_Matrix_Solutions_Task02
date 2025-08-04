# Brainwave_Matrix_Solutions_Task02
📄 Project Summary: Amazon Review Sentiment Analysis
This project focuses on understanding customer sentiments through the analysis of Amazon product reviews. The main objective is to build an effective sentiment classification model that can accurately predict whether a given review is positive, neutral, or negative.

🧹 Data Cleaning and Preprocessing
The raw text data was first preprocessed using Spacy, which involved:

Removing stopwords, punctuation, and special characters

Lowercasing all text

Lemmatization to normalize words (e.g., "running" → "run")

Additional filtering steps ensured that empty reviews and non-informative rows were dropped to improve data quality.

🧠 Sentiment Classification
A Logistic Regression classifier was trained using TF-IDF vectorized text features.

The dataset was split into training and testing sets to evaluate the model’s generalization.

The model achieved strong performance in classifying reviews into sentiment categories.

📊 Visual Analysis and Insights
WordClouds were generated for each sentiment class to visually represent the most common words in:

Positive Reviews (e.g., “great”, “love”, “excellent”)

Neutral Reviews (e.g., “okay”, “average”, “fine”)

Negative Reviews (e.g., “bad”, “poor”, “worst”)

A pie chart displayed the proportion of each sentiment class, providing an overall picture of customer mood.

A line plot was used to analyze sentiment trends over time, revealing fluctuations in user satisfaction.

🧪 Model Evaluation
The model’s performance was evaluated using:

Accuracy Score on the test set

Confusion Matrix to visualize true vs. predicted classes

The classifier performed well in identifying dominant sentiment classes, although some confusion was observed between neutral and positive reviews — a common challenge in sentiment tasks.

🧾 User-Level Prediction
An interactive prediction block allows users to input their own review and receive a predicted sentiment in real-time.

This enhances the practicality and real-world applicability of the project.

💾 Final Export and Reusability
The cleaned and labeled dataset was saved as a cleaned_reviews.csv file for future use or further analysis.
