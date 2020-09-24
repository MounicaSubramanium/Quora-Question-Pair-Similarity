# Quora-Question-Pair-Similarity
This project was involved a Kaggle competition hosted by Quora.com in finding which questions on Quora are duplicates of questions that have already been asked. Predictions were also made whether a pair of questions are duplicates or not.

- It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.
- Used Natural Language Processing and Fuzzy Features for Advanced feature extraction.
- Compared Logistic Regression, Linear SVM, and XGBoost for finding the best model for classification.

Kaggle Link -
https://www.kaggle.com/c/quora-question-pairs/overview


## Table of contents
* [General info](#general-info)
* [Setup](#setup)
* [Status](#status)
* [Contact](#contact)

## General info

Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

Refer to the jupyter notebook named 'Quora.ipynb' for more information.

## Setup

1. Download the repository on your computer.
2. Use the links given below to download important files(.csv files, databases) associated with the project -

- training data 'Train.csv' file.
https://drive.google.com/file/d/10QDGTSI5PEV9e7CTpfzsXRpUwRIsJA-J/view

- 'df_fe_without_preprocessing_train.csv' -
https://drive.google.com/file/d/1gTfCTD3fz-3NJnfYLm59nZFN3WC3fzfD/view?usp=sharing

- 'nlp_features_train.csv'- 
https://drive.google.com/file/d/1JncN1Fyt-ND_yZXOzqEfcRsYMTKqtu7Q/view?usp=sharing

- 'final_features.csv'-
https://drive.google.com/file/d/1S1gLTaumYwEBPbH677Jr9erECVUdvAhv/view?usp=sharing

- Database file -
https://drive.google.com/file/d/1A5dzEvSpxXYQ5LKgtklor4jWdDV8y_4i/view

- Link to text files -
   a. train_n.txt
      https://drive.google.com/file/d/1peorE_ke1MoaZCkrNQpap1ozJ15fuk2s/view?usp=sharing

   b. train_p.txt -
     https://drive.google.com/file/d/19KsWPoIMX3O_FrT4We0I1M7reKvFYKRr/view?usp=sharing


3. Run the Jupyter notebooks in the following order -

- Quora.ipynb
- Quora_Preprocessing.ipynb
- Q_Mean_W2V.ipynb
- ML_models.ipynb

Follow along the project flow to know the right time of using the downloaded files.

### Install the requirements
 
* Install the requirements using `pip install -r requirements.txt`.
    * Make sure you use Python 3.
    

## Status
Project Status: Complete


## Contact
Feel free to contact me, shoot a email to **pranshu1921@gmail.com**
