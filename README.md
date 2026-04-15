# Spam Email Detector

A machine learning project that detects whether an email is spam or not spam using Natural Language Processing (NLP) and classification algorithms.

## Features

- Detects spam emails from subject and body text.
- Uses text preprocessing and TF-IDF vectorization.
- Trained with a machine learning classifier.
- Simple and easy to test with custom input.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Flask or Streamlit

## Project Structure

```bash
spam-email-detector/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
└── data/
    └── spam.csv
```

## How It Works

1. Load the dataset of spam and ham emails.
2. Clean and preprocess the text data.
3. Convert text into numerical format using TF-IDF.
4. Train a classifier such as Naive Bayes or Logistic Regression.
5. Predict whether a new email is spam or not.

## Installation

```bash
git clone https://github.com/your-username/spam-email-detector.git
cd spam-email-detector
pip install -r requirements.txt
```

## Usage

Run the project:

```bash
python app.py
```

Example input:

```python
subject = "Congratulations! You won a free gift"
body = "Click the link now to claim your prize."
```

Example output:

```python
Prediction: Spam
```

## Dataset

This project uses a labeled dataset containing:
- Spam messages
- Ham messages

## Model Performance

The model can be evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Future Improvements

- Add real-time email integration.
- Improve detection with better NLP models.
- Add phishing email detection.
- Build a nice web interface.

## License

This project is open-source and available under the MIT License.

## Author
Created by : Ramya
