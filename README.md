# SENTIMENT-ANALYSIS

*COMPANY* :CODTECH IT SOLUTIONS

*NAME* :SIDDAMMAGARI CHANDANA

*INTERN ID* :CT06DF1118

*DOMAIN* :DATA ANALYTICS

*DURATION* :6 WEEKS

*MENTOR* :NEELA SANTHOSH KUMAR

Project Description

**A Sentiment Analysis Approach to Airline Tweets Using VADER and NLP Techniques**

This project is a complete implementation of sentiment analysis using Natural Language Processing (NLP) techniques on a real-world Twitter dataset. The goal is to analyze the sentiment of tweets related to airlines and classify them into Positive, Negative, or Neutral categories. This project was developed as part of Task 4 – Sentiment Analysis for the CodTech Data Analysis Internship.

**Objective**

The main objective of this project is to apply basic NLP tools to extract meaningful insights from user-generated text on Twitter. This type of sentiment analysis has wide applications in industries including aviation, e-commerce, entertainment, and customer service. In this case, we focus on the Twitter US Airline Sentiment dataset, which includes tweets by users expressing opinions about major U.S. airlines.

**Dataset Details**

The dataset used for this project is publicly available on Kaggle under the title Twitter US Airline Sentiment. It contains over 14,000 tweets directed at six U.S. airlines including American, United, Southwest, Delta, US Airways, and Virgin America.

Each tweet in the dataset includes:

The tweet text

Airline name

Manually labeled sentiment (positive, neutral, or negative)

Tweet ID and additional metadata

This dataset provides a rich source for training and evaluating sentiment classification models.

**Tools and Technologies Used**

Python: Core programming language

Google Colab: Cloud-based notebook environment used for development

NLTK (Natural Language Toolkit): For accessing the VADER sentiment analyzer

Pandas: For data manipulation and processing

Matplotlib & Seaborn: For visualizing sentiment distributions

Scikit-learn: For performance evaluation (confusion matrix, classification report)

**Methodology**

Data Loading and Cleaning
The dataset is loaded using pandas, and unnecessary columns are removed. We retained only the tweet text and the sentiment label for further analysis. Missing or null entries were filtered out to ensure clean input data.

Sentiment Analysis with VADER
The project uses the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analyzer from the NLTK library. VADER is especially effective for short, informal texts like tweets.

Each tweet is passed through the VADER model to compute a compound score, which reflects the overall sentiment.

Based on the compound score, the sentiment is categorized:

Score ≥ 0.05 → Positive

Score ≤ -0.05 → Negative

Otherwise → Neutral

**Sentiment Label Comparison**

After predicting sentiment using VADER, we compare it to the original human-labeled sentiment from the dataset. This helps evaluate the model’s performance and identify where the rule-based approach works well or struggles.

**Evaluation and Visualization**
The results are analyzed using:

A confusion matrix and classification report (accuracy, precision, recall, F1-score)

Bar charts that visualize both actual and predicted sentiment distributions

These visualizations help understand model behavior and how user sentiment is distributed across the dataset.

**Key Findings**

The dataset is highly imbalanced, with the majority of tweets being negative.

VADER sentiment analysis performs reasonably well on this dataset, especially for clearly polarized tweets.

Most misclassifications occur in neutral vs negative categories, likely due to subtle sarcasm or implicit language that VADER struggles with.

The tool is effective for quick sentiment tagging but may need enhancements (like ML models) for better accuracy in production environments.

**Conclusion**

This project successfully demonstrates a full NLP pipeline from raw data to analysis using rule-based sentiment classification. It provides a hands-on application of text analysis with real-world data and explores both the strengths and limitations of basic sentiment models. The project is simple yet effective and can be extended in the future using machine learning or deep learning techniques for higher accuracy and adaptability.

**OUTPUT**

![Image](https://github.com/user-attachments/assets/292bffeb-7288-499a-84f3-da94fddf6460)
