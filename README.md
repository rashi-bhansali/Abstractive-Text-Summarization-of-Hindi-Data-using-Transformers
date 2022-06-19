# Abstractive-Text-Summarization-of-Hindi-Data-using-Transformers
A transformer encoder decoder based approach for abstracting salient information from Hindi news articles, to generate a human-like headline summary.
This model is trained on the "Hindi Text Short Summarization Corpus" data with about 0.3 million news articles, available on Kaggle https://www.kaggle.com/datasets/disisbig/hindi-text-short-summarization-corpus
This approach also uses the FastText pre-trained word embedding, released by Facebook, trained on Hindi wikipedia and news articles. The pre-trained embedding weights are used to initialize the vectors before passing to the transformer encoder and decoder modules.
In order to train the model from scratch on the entire data, minimum 12 GB RAM and atleast 2 GPU cores with 0.82GHz / 1.59GHz memory clock are needed.
For using the trained model for summarizing single-document text, use the "predict()" function present in summary.py file.
