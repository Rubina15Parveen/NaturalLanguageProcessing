<!DOCTYPE html>
<html> 
<body>
      <h1> Natural Language Processing </h1>
            <div>
                   This repository contains a collection of small assignments designed to introduce the core concepts and techniques in                         Natural Language Processing (NLP). Each notebook showcases a specific NLP task, and the projects are structured to help                      build foundational understanding in the field.
            </div>
      <h4> Files and Projects <h4/>
            <div>
                   1. N_grams.ipynb
                        <p>
                            <br> Implements trigram models using the corpus_for_language_model.txt file.
                            <br> Trains n-grams and calculates sentence probabilities using various techniques:
                            <br> -- Maximum Likelihood Estimation (MLE)
                            <br> -- Laplace Smoothing
                            <br> -- Katz Backoff
                            <br>Computes Positive Pointwise Mutual Information (PPMI) for word pairs based on the corpus.
                            <br>Leverages GloVe embeddings to find the most similar words. GloVe embeddings are downloaded and extracted                                     using the following commands:
                            <br>!wget http://nlp.stanford.edu/data/glove.42B.300d.zip
                            <br>!unzip glove.42B.300d.zip<br>
                        </p>
              </div>
              <div>
                   2. Emotions_Sentiment_Analysis.ipynb 
                  <br> This notebook focuses on a variety of NLP tasks using both classical and neural approaches:
                  <br>  (i) Classical Part-of-Speech Tagging
                              <p> Uses the Spacy library to perform statistical Part-of-Speech (POS) tagging. install: python -m spacy                                         download en_core_web_sm 
                              </p> 
                  <br> (ii) Neural Part-of-Speech Tagging
                               <p> Utilizes the Transformers library for neural POS tagging. Model :QCRI/bert-base-multilingual-cased-pos-                                      english (a multilingual BERT model trained on the Penn Treebank dataset). Tags sentences using a neural                                      network-based BERT model.
                               </p>
                  <br> (iii) Neural Sentiment Analysis
                               <p> Uses the Transformers library for sentiment analysis on tweets. Model: "cardiffnlp/twitter-xlm-roberta-                                      base-sentiment" (an XLM-R model fine-tuned for multilingual sentiment analysis). Performs sentiment                                          analysis on Twitter data. 
                               </p>
                  <br> (iv) Neural Emotion Detection
                                <p> Uses the Transformers library for emotion detection on tweets. Model: "mrm8488/t5-base-finetuned-                                            emotion" (a T5 model fine-tuned for emotion recognition). Predicts the emotion in each tweet based on                                        Google's T5 architecture.
                                </p>
            </div>
</body>
</html>
