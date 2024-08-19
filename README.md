
# Toxic Comment Classification Project
Kaggle recently ran a toxic comment classification challenge. https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

This project focuses on the classification of toxic comments using various machine learning models and techniques. The project is divided into several notebooks, each addressing different aspects of the problem, such as exploratory data analysis (EDA), feature extraction using word embeddings, and building classifiers for toxic and non-toxic comments using CNN, Bidirectional LSTM, CNN, Ensemble Models.

## Project Structure
Toxic Comment EDA: This notebook performs exploratory data analysis on the toxic comments dataset. It includes data visualization, statistics, and insights into the distribution of toxic and non-toxic comments. Toxic Comments using Word Embeddings: This notebook demonstrates how to extract features from the text data using word embeddings like Word2Vec, GloVe, and FastText. It also prepares the data for training machine learning models. Toxic Comment Classifier: This notebook builds and trains a classifier to detect toxic comments. The model is trained on the features extracted in the previous step and evaluated using various metrics. Non-Toxic Comment Classifier: This notebook builds and trains a classifier to detect non-toxic comments. Similar to the previous classifier, it uses features extracted from the text data and is evaluated on performance metrics.

## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository: bash pip install -r requirements.txt

## Installation
```bash
 
!pip install pandas==1.3.3
!pip install numpy==1.21.2
!pip install matplotlib==3.4.3
!pip install seaborn==0.11.2
!pip install scikit-learn==0.24.2
!pip install tensorflow==2.6.0
!pip install keras==2.6.0
!pip install nltk==3.6.3
!pip install wordcloud==1.8.1
```

## Run 
-Toxic Comment EDA: Start with this notebook to get insights into the dataset. Run all cells sequentially to explore the data. Please use the Kaggle Dataset folder for this to run it.

-Toxic Comments using Word Embeddings: Execute this notebook to generate word embeddings from the text data. Make sure the embeddings are stored correctly for use in the classifier notebooks. Please use the Glove embeddings file to run the code.

- Toxic Comment Classifier: Run this notebook to train and evaluate the toxic comment classifier. Use the toxicity-types-data to run this code.

-Non-Toxic Comment Classifier: Finally, run this notebook to train and evaluate the non-toxic comment classifier.Use the toxic-nontoxic-data to run this code.


