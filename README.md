# CSSM530-Project
GitHub Repo for CSSM530 Final Research Paper - Political Ideology Classification in Turkish Tweets

1. [Read Annotation Data - Final Annotator](https://github.com/melihcanyardi/CSSM530-Project/blob/main/read_annotation_data_final_annotator.ipynb): Read and combine annotation data, filter for "final" annotator, exploratory data analysis
2. [Read Annotation Data - All Annotators](https://github.com/melihcanyardi/CSSM530-Project/blob/main/read_annotation_data_all_annotators.ipynb): Read and combine annotation data, create "multiple" annotator by summing annotations of different annotators, exploratory data analysis
3. [Data and Text Preprocessing](https://github.com/melihcanyardi/CSSM530-Project/blob/main/data_and_text_preprocessing.ipynb): Data preprocessing (remove multilabelled tweets, create "label" column from multiple label columns, equating two data sets by removing nonmutual tweets) and text processing for tweet texts (lowercasing, emoji processing, removing non-alphanumeric characters, removing stop words, tokenization, and lemmatization)
4. [Model and Settings Comparison](https://github.com/melihcanyardi/CSSM530-Project/blob/main/model_and_settings_comparison.ipynb): Comparison of different settings (Feature extraction methods: Bag-of-Words and TF-IDF; N-Gram Ranges: (1, 1), (1, 2), (1, 3), (2, 2), (2, 3), (3, 3); Lemmatizations: True (Lemmatized) and False (Not lemmatized); Annotators: Final (“final_annotator” labels) and All (“all_annotators” labels)) and classification models (Logistic Regression, Multinomial Naïve Bayes, and Support Vector Machine, Random Forest, K-Nearest Neighbor)

[scores.csv](https://github.com/melihcanyardi/CSSM530-Project/blob/main/scores.csv): F1 scores for the compared settings and classification models
