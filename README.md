# Sentimental analysis of air-line review

## Objective:
- Perform sentimental analysis of the air-line review and user specific feedback
- And the advance knowledge in the NLP task.
  
## Overview
- The system takes a review as a input (Containing the user given review and specific tag such as amazing , okayish , great etc..) and system will classify it as positive or negative review.
  
## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- NumPy
- nltk


### Dataset
- The dataset used is provided in this repo.

### How it works
- The system uses the following steps for the sentimental analysis:
### Data Preprocessing:
- Load the dataset and preprocess the data (e.g., handle missing values, convert categorical variables to numerical values).
The data is preprocessed using NLP(natural language processing) techniques. (PorterStemmer etc.)
- mostly this part for to clean the language for the most effetive sentimental analysis.
### Feature Extraction:
- Extract features from the cleaned data.
### Sentmental Analysis:
- #### Model : MultinomialNB
- This model has given accuracy of 98% for the given daataset , but may vary and lessen also for the dataset other than this.
