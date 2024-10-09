# Machine Learning Email Classifier

## Project Overview

This project uses a machine learning model to classify emails as either spam or ham (non-spam) based on content. The dataset is extracted from the Enron email corpus, and the model is trained to distinguish between legitimate and spam emails using natural language processing (NLP) techniques.

## Key Features

- **Dataset**: Emails from the Enron corpus categorized as spam or ham.
- **Text Preprocessing**: Non-alphabet characters removed and text normalized to lowercase for consistent analysis.
- **Model**: Logistic Regression trained using word frequency data (vectorized text) to classify emails.
- **Evaluation**: Model performance evaluated through accuracy, confusion matrix, and classification report.

## Technologies Used

- **Python**: Data processing and model training
- **Pandas**: Data manipulation
- **Scikit-learn**: Machine learning (Logistic Regression, vectorization, and model evaluation)

## Outcomes

- Achieved **97.38% accuracy** in classifying spam and ham emails.
- **Top Spam Indicators**: Words like "http," "prices," and "remove."
- **Top Ham Indicators**: Words like "attached," "thanks," and "enron."
- Insights into which words significantly contribute to email classification.

## Conclusion

This project demonstrates the effectiveness of machine learning in text classification tasks like spam detection. By identifying key features and applying a logistic regression model, we achieved high accuracy in distinguishing between spam and legitimate emails.

## Links

https://medium.com/@ronak.kumar1023/unlocking-cybersecurity-skills-jp-morgan-chase-co-job-simulation-by-forage-eea0f78564f0

