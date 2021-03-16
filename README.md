# Text-Mining-with-movie-scripts

## General info
In this project, we will use a dataset of movie scripts to perform some Text Mining tasks like classification, clustering, and topic analysis.
The dataset was built by scraping some web pages with the scripts of the movies and then enriched by integrating pieces of information using tmdb API, 
for the purpose of this project, we will use just the raw corpus of the scripts and the Infos about the main genres of each movie.
The movies scripts are represented via a multitude of ways, first of all by a document-term matrix, then we investigated more complex ways of
representing the long and sparse nature of the data, we used dimensionality reduction methods as SVD (https://en.wikipedia.org/wiki/Singular_value_decomposition),
Word2Vec (https://en.wikipedia.org/wiki/Word2vec) and GloVe (https://en.wikipedia.org/wiki/GloVe_(machine_learning)), we then used these word embeddings to perform our tasks
and analysis, we also used t-SNE (https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding) to reduce even more the dimensionality to just 2 components to visualize our scripts in a plane. 

## Technologies
Project is created with:
* numpy
* scipy
* IPython
* pandas
* nltk
* tensorflow
* sklearn
* matplotlib
* gensim
* pyLDAvis

## Needed Files:
to obtain `glove.6B.300d.txt.word2vec` follow [these steps](https://www.techunits.com/topics/neural-networks/shallow-neural-network/how-to-convert-a-pre-trained-glove-vector-into-word2vec-format/)

to obtain the pre-trained Doc2Vec files download [English Wikipedia Skip-Gram (1.4GB)](https://unimelbcloud-my.sharepoint.com/:u:/g/personal/jeyhan_lau_unimelb_edu_au/EU2lteQ-nlNLn127cVR2mzYBPwcUE-_ZxDtjjXtKNMC33A?e=4Z2Zoo)
