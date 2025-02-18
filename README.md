# MedInsight: A Personalized Prescription Recommendation Using Machine Learning

## Overview
MedInsight is a Machine Learning-based system designed to provide personalized prescription recommendations by analyzing patient reviews using Natural Language Processing (NLP) techniques. The system leverages various classification models to extract insights from patient-generated data and recommend suitable medications based on medical conditions.

## Features
- **Personalized Drug Recommendations**: Uses patient reviews to classify medical conditions and suggest appropriate medications.
- **Machine Learning Models**: Implements Naive Bayes, Passive Aggressive Classifiers, Random Forest, SVM, Extra Trees Classifier and Logistic Regression models.
- **Natural Language Processing (NLP)**: Utilizes TF-IDF vectorization, bigrams, and trigrams to enhance classification accuracy.
- **Efficient Data Processing**: Preprocessing includes stopword removal, lemmatization, and feature extraction.
- **High Classification Accuracy**: Achieves up to 98.5% accuracy using optimized ML techniques.

## Installation & Execution in Google Colab
### Prerequisites
Ensure you have a Google account to access Google Colab.

### Steps to Run in Google Colab
1. Open Google Colab: [Google Colab](https://colab.research.google.com/)
2. Upload the required files to Colab:
   - Click on the **Files** tab on the left.
   - Upload your dataset.
3. Run the code:
4. Generate drug recommendations:
   - Use test reviews from the drugsComTest_raw to generate top 3 drug recommendations

## Data Preprocessing
- **HTML Tag Removal**: Eliminates unnecessary HTML elements.
- **Lowercasing**: Ensures uniformity in text data.
- **Stopword Removal**: Removes common words to improve text analysis.
- **Lemmatization**: Reduces words to their root forms.
- **Feature Extraction**: Implements TF-IDF and N-grams for textual representation.

## Machine Learning Models Used
- **Naive Bayes Classifier (without TF-DF, with TF-IDF)**
- **Passive Aggressive Classifier (without TF-DF, with TF-IDF [unigrams, bigrams, trigrams])**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Extra Trees Classifier**

## Evaluation Metrics
- **Accuracy**: Measures correctly classified instances.
- **Precision, Recall, and F1-Score**: Evaluate model performance for various conditions.

## Example Usage in Google Colab
```python
--review "I have been experiencing anxiety and need medication recommendations."
```
**Output:**
```
Condition: Anxiety

Top 3 Suggested Drugs:

Xanax
Sertraline
Prozac
```
