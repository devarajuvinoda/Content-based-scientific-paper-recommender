# Content-based-scientific-paper-recommender
A citation-agnostic document embeddings for research paper recommendations using Doc2Vec, Universal Sentence Encoder and sentence-BERT.

To design our scientific paper recommender we implemented five different approaches, TF-IDF, LSTM-based word em- beddings, Doc2Vec, Sentence-BERT and Universal Sentence Encoder(USE). 
  * TF-IDF gave good result based on specific words. 
  * sentence-BERT and USE are good at giving recom- mendations even query does not have specific key-words. 
  * Doc2Vec and LSTM based methods gave poor results.

Below is the snapshot of sample recommendations by each model for a given input query.
  
  <p align="center">
  <img src="https://github.com/devarajuvinoda/Content-based-scientific-paper-recommender/blob/main/tfidf_d2v_use.png" width="400" title="hover text">
  <img src="https://github.com/devarajuvinoda/Content-based-scientific-paper-recommender/blob/main/lstm_sent_bert.png" width="400" alt="accessibility text">
</p>
