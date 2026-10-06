# Airline Review Sentiment Analysis

A classical NLP project that classifies airline-related Twitter reviews into sentiment categories using text preprocessing and a Multinomial Naive Bayes classifier.

## Objective

The project explores a traditional machine-learning workflow for text classification:

```
Raw airline review
      ↓
Text cleaning / preprocessing
      ↓
Feature extraction
      ↓
Multinomial Naive Bayes
      ↓
Sentiment prediction
```

The notebook uses the airline Twitter review dataset included in the repository and removes neutral samples for the binary sentiment analysis stage.

## Dataset

The repository contains `Tweets.csv`, with 14,640 records and fields including sentiment labels, airline information, negative-reason categories, timestamps, and review text.

## Model

**Multinomial Naive Bayes**

The original notebook reports approximately **98% accuracy** for the evaluated dataset. Treat this as a dataset-specific result rather than a generalization guarantee.

## Technology

**Python · Pandas · NumPy · scikit-learn · NLTK · Jupyter Notebook**

## Repository structure

```
.
├── Tweets.csv
├── main.ipynb
├── requirements.txt
└── README.md
```

## Run the notebook

Create a virtual environment and install the dependencies:

```bash
python -m venv .venv
pip install -r requirements.txt
```

Then open `main.ipynb` in Jupyter and run the cells sequentially.

## Why this project is useful

Although it is a classical ML project, it demonstrates several fundamentals that remain important in applied NLP and ML engineering:

- preparing messy text data;
- transforming text into model-ready features;
- training a probabilistic classifier;
- evaluating a classification model;
- understanding how dataset assumptions affect reported performance.

## Possible improvements

- add a reproducible train/validation/test split with fixed random seeds;
- compare Naive Bayes with linear SVM or logistic regression;
- add precision, recall, F1, and a confusion matrix;
- package preprocessing and inference into reusable functions;
- expose the classifier through a small API.

## Author

**Ronak Vekariya**

[GitHub](https://github.com/Ronakvekariya)
