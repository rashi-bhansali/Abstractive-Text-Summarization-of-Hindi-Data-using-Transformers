# Abstractive-Text-Summarization-of-Hindi-Data-using-Transformers
A transformer encoder decoder based approach for abstracting salient information from Hindi news articles, to generate a human-like headline summary.
This model is trained on the "Hindi Text Short Summarization Corpus" data with about 0.3 million news articles, available on Kaggle https://www.kaggle.com/datasets/disisbig/hindi-text-short-summarization-corpus
This approach also uses the FastText pre-trained word embedding, released by Facebook, trained on Hindi wikipedia and news articles, available at https://fasttext.cc/docs/en/crawl-vectors.html 
The pre-trained embedding weights are used to initialize the vectors before passing to the transformer encoder and decoder modules.
In order to train the model from scratch on the entire data, make sure to download the data and embeddings files from the links mentioned above. As the data is huge,  minimum 16 GB RAM and GPU Tensor cores with 300+ gb/s bandwidth are needed. For experimental purposes, model can be trained on smaller data.
