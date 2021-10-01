# Content-based-scientific-paper-recommender
A citation-agnostic document embeddings for research paper recommendations using Doc2Vec, Universal Sentence Encoder and sentence-BERT.

To design our scientific paper recommender we implemented five different approaches, TF-IDF, LSTM-based word em- beddings, Doc2Vec, Sentence-BERT and Universal Sentence Encoder(USE). 
  * TF-IDF gave good result based on specific words. 
  * sentence-BERT and USE are good at giving recommendations even query does not have specific key-words. 
  * Doc2Vec and LSTM based methods gave poor results.

Below is the snapshot of sample recommendations by each model for a given input query.
  
 <p align="center">
  <img src="https://github.com/devarajuvinoda/Content-based-scientific-paper-recommender/blob/main/tfidf_d2v_use.png" width="700" title="TF-IDF, Doc2Vec and Universal Sentence Encoder">
</p>

<p align="center">
  <img src="https://github.com/devarajuvinoda/Content-based-scientific-paper-recommender/blob/main/lstm_sent_bert.png" width="700" title="Sentence-BERT and LSTM Based Embeddings">
</p>

We selected three research papers known to us from 3 dif- ferent categories (cs.CV - computer vision, cs.LG - machine learning and cs.RO - robotics) as a search query. We obtained top 10 recommendations for each query and rated how many of the papers are rele- vant out of 10 papers and the score plot is as shown below,
 <p align="center">
  <img src="https://github.com/devarajuvinoda/Content-based-scientific-paper-recommender/blob/main/score_res.png" width="400" title="Relevance Score Plot.">
</p>
