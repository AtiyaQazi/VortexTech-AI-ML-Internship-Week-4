
# VortexTech AI/ML Internship — Week 4

## Sentiment Analysis Model

This project is the final capstone task of the **VortexTech AI & ML Internship Track**. It focuses on Natural Language Processing (NLP) and machine learning to classify movie reviews as **Positive** or **Negative**.

The project uses the **IMDB 50K Movie Reviews dataset** and implements a complete sentiment analysis pipeline, from text preprocessing to model evaluation and custom sentiment prediction.

## Project Objectives

- Load and explore a public sentiment-labeled dataset.
- Clean and preprocess text data.
- Convert text into numerical features using TF-IDF.
- Train a Logistic Regression classification model.
- Evaluate the model using accuracy, F1-score, and a confusion matrix.
- Test the model on three custom review sentences.

## Dataset

**Dataset:** IMDB 50K Movie Reviews

- Total reviews: 50,000
- Positive reviews: 25,000
- Negative reviews: 25,000
- Training samples: 40,000
- Testing samples: 10,000

The dataset contains movie reviews labeled as either positive or negative.

## Technologies and Libraries

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Load and inspect the dataset.
2. Analyze sentiment distribution.
3. Analyze review length.
4. Clean the text:
   - Convert text to lowercase.
   - Remove HTML tags.
   - Remove special characters.
   - Remove stopwords.
   - Apply lemmatization.
5. Convert cleaned reviews into TF-IDF features.
6. Split the data into training and testing sets.
7. Train a Logistic Regression model.
8. Evaluate model performance.
9. Test the model on custom review sentences.

## Model

**Classification Algorithm:** Logistic Regression

**Feature Extraction:** TF-IDF

**Maximum TF-IDF Features:** 5,000

## Results

| Metric | Result |
|---|---:|
| Dataset Size | 50,000 |
| Training Samples | 40,000 |
| Testing Samples | 10,000 |
| TF-IDF Features | 5,000 |
| Model | Logistic Regression |
| Accuracy | 89.19% |
| Negative F1-score | 0.89 |
| Positive F1-score | 0.89 |

## Custom Predictions

The trained model was tested on three custom sentences:

| Example | Predicted Sentiment |
|---|---|
| This movie was absolutely amazing! | Positive |
| The movie was boring and a complete waste of time. | Negative |
| I really enjoyed this film because the story was exciting. | Positive |

## Limitation

The model may struggle with sarcasm, complex context, and reviews containing both positive and negative opinions. Since the model learns patterns from the training data, it may not always understand the deeper meaning of a sentence.

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/AtiyaQazi/VortexTech-AI-ML-Internship-Week-4.git