# movie-sentiment-analysis
Exploring the use of CNNs on Sparse encodings. This is adapted from my Applied Machine Learning mini-project at The University of Edinburgh.

'data_cleaning_and_EDA.ipynb': Juypter Notebook that details the cleaning and exploratory data analysis for the Stanford Movie Review phrase dataset

'NNs_and_evaluation.ipynb': Juypter Notebook that compares the dense and convolutional Keras neural networks used to classify sentiment.

The full project also includes the comparison of different phrase encodings (Word2Vec and TF-IFD) along with their performance. Sentence data is also used to test the predictions of the model.

The best performing model was found to be the CNN on the sparse matrix encodcoding, this model also exhibited the least overfitting. However, all encodings and models struggled to classify extreme sentiment (i.e. very positive and very negative) correctly. This most likely due to the limited number of training samples of these sentiments within the dataset.
