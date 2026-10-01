# 📧 Email Spam Classifier

A machine learning project that classifies text messages as **spam** or **ham (not spam)** using Natural Language Processing (NLP).

## 📌 Project Overview

This project uses the **SMS Spam Collection dataset**, containing 5,572 labeled messages.

Text messages are transformed into numerical features using **TF-IDF**, and a **Multinomial Naive Bayes** classifier is trained to distinguish spam from legitimate messages.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- TF-IDF Vectorization
- Multinomial Naive Bayes

## ⚙️ Method

1. Load and inspect the dataset
2. Convert labels into numerical values
3. Split the data into training and testing sets
4. Transform text using TF-IDF
5. Train a Multinomial Naive Bayes classifier
6. Evaluate the model using accuracy, classification metrics, and a confusion matrix
7. Test the model on custom email/message examples

## 📊 Results

The model achieved approximately **97.04% accuracy** on the test set.

| Metric | Ham | Spam |
|---|---:|---:|
| Precision | 97% | 100% |
| Recall | 100% | 78% |
| F1-Score | 98% | 88% |

### Confusion Matrix

- 966 ham messages correctly classified as ham
- 116 spam messages correctly classified as spam
- 33 spam messages misclassified as ham
- 0 ham messages misclassified as spam

## 🧪 Example

The trained model can classify new messages such as:

> "Congratulations! You won a free prize today!"

**Prediction:** Spam

## 🚀 Future Improvements

- Compare multiple machine learning algorithms
- Improve spam recall
- Experiment with n-grams and TF-IDF parameters
- Apply hyperparameter tuning
- Deploy the classifier as a simple web application

## 📚 What I Learned

This project helped me practice:

- Natural Language Processing fundamentals
- Text preprocessing and feature extraction
- TF-IDF vectorization
- Training and evaluating classification models
- Interpreting precision, recall, F1-score, and confusion matrices
- 
