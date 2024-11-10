<!DOCTYPE html>
<html> 
<body>
      <h1> Natural Language Processing </h1>
            <div>
                  <p>
                   This repository contains a collection of small assignments designed to introduce the core concepts and techniques in                         Natural Language Processing (NLP). Each notebook showcases a specific NLP task, and the projects are structured to help                      build foundational understanding in the field.
                  </p>            
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
                   <br> 2. Emotions_Sentiment_Analysis.ipynb <br>
                  <br> This notebook focuses on a variety of NLP tasks using both classical and neural approaches: <br><br>
                   (i) Classical Part-of-Speech Tagging
                              <p> Uses the Spacy library to perform statistical Part-of-Speech (POS) tagging. install: python -m spacy                                         download en_core_web_sm 
                              </p> 
                   (ii) Neural Part-of-Speech Tagging
                               <p> Utilizes the Transformers library for neural POS tagging. Model :QCRI/bert-base-multilingual-cased-pos-                                      english (a multilingual BERT model trained on the Penn Treebank dataset). Tags sentences using a neural                                      network-based BERT model.
                               </p>
                   (iii) Neural Sentiment Analysis
                               <p> Uses the Transformers library for sentiment analysis on tweets. Model: "cardiffnlp/twitter-xlm-roberta-                                      base-sentiment" (an XLM-R model fine-tuned for multilingual sentiment analysis). Performs sentiment                                          analysis on Twitter data. 
                               </p>
                  (iv) Neural Emotion Detection
                                <p> Uses the Transformers library for emotion detection on tweets. Model: "mrm8488/t5-base-finetuned-                                            emotion" (a T5 model fine-tuned for emotion recognition). Predicts the emotion in each tweet based on                                        Google's T5 architecture.
                                </p>
            </div>
            div>
                   3. Neural_QA,_Summarization_and_Dependency_Parsing.ipynb<br>
                        <p>
                            <br> (i) Neural Question Answering: Using the Hugging Face Transformers library to load and implement various question-answering models, we answer specific questions based on provided contexts. Each model is assessed for its ability to generate accurate answers, and the code is structured to allow easy experimentation with different models.
                            <br> (ii) Neural Summarization: Utilizing Transformers for abstractive summarization, we apply multiple models to condense long passages into concise summaries. Each model is evaluated for effectiveness in capturing the main points of the text while maintaining coherence and readability.
                            <br> (iii) Dependency Parsing with SpaCy: Using the SpaCy library, we explore syntactic relationships within sentences by performing dependency parsing with different SpaCy models. This analysis helps understand the grammatical structure of sentences and the relationships between words.
                        </p>
              </div>
</body>
</html>
