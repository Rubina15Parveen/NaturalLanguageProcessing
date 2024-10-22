<!DOCTYPE html>
<html> 
<body>
      <h1> Natural Language Processing </h1>
      <div>
            This repository contains a collection of small assignments designed to introduce the core concepts and techniques in Natural Language Processing (NLP). Each notebook showcases a specific NLP task, and the projects are structured to help build foundational understanding in the field.
      </div>
<br>  <h4> Files and Projects <h4/>
      <div>
      <br> &ensp;1. N_grams.ipynb
      <br> &ensp;Implements trigram models using the corpus_for_language_model.txt file.
      <br> &ensp;Trains n-grams and calculates sentence probabilities using various techniques:
      <br> &ensp;&ensp;-- Maximum Likelihood Estimation (MLE)
      <br> &ensp;&ensp;-- Laplace Smoothing
      <br> &ensp;&ensp;-- Katz Backoff
      <br>&ensp;Computes Positive Pointwise Mutual Information (PPMI) for word pairs based on the corpus.
      <br>&ensp;Leverages GloVe embeddings to find the most similar words. GloVe embeddings are downloaded and extracted using the following commands:
        <br>&ensp;&ensp;!wget http://nlp.stanford.edu/data/glove.42B.300d.zip
        <br>&ensp;&ensp;!unzip glove.42B.300d.zip<br>
        </div>
        <div>
      <br> &ensp;2. Emotions_Sentiment_Analysis.ipynb 
      <br>&ensp;&ensp; This notebook focuses on a variety of NLP tasks using both classical and neural approaches:
      <br> &ensp;&ensp;&ensp;&ensp; (i) Classical Part-of-Speech Tagging
      <br> &ensp;&ensp;&ensp;&ensp; Uses the Spacy library to perform statistical Part-of-Speech (POS) tagging.
      <br> &ensp;&ensp;&ensp;&ensp; install: python -m spacy download en_core_web_sm
      <br> &ensp;&ensp;&ensp;&ensp; (ii) Neural Part-of-Speech Tagging
          <p> <br> &ensp;&ensp;&ensp;&ensp; Utilizes the Transformers library for neural POS tagging. Model :QCRI/bert-base-multilingual-cased-pos-english (a multilingual BERT model trained on the Penn Treebank dataset). Tags sentences using a neural network-based BERT model.
          </p>
      <br> &ensp;&ensp;&ensp;&ensp;  (iii) Neural Sentiment Analysis
      <br> &ensp;&ensp;&ensp;&ensp;        <p> Uses the Transformers library for sentiment analysis on tweets. Model: "cardiffnlp/twitter-xlm-roberta-base-sentiment" (an XLM-R model fine-tuned for multilingual sentiment analysis). Performs sentiment analysis on Twitter data. </p>
      <br> &ensp;&ensp;&ensp;&ensp;  (iv) Neural Emotion Detection
      <br> &ensp;&ensp;&ensp;&ensp;   <p> Uses the Transformers library for emotion detection on tweets. Model: "mrm8488/t5-base-finetuned-emotion" (a T5 model fine-tuned for emotion recognition). Predicts the emotion in each tweet based on Google's T5 architecture.
      </p>
      </div>
</body>
</html>
