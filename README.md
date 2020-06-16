# DeepLearning-NLP-GenerateWordEmbeddings
Use the IMDb dataset to generate word embedding as we train our dataset. This dataset contains 25,000 movie reviews from IMDB, labeled with a sentiment (positive or negative).

Generate Word Embedding and retrieve outputs of each layer with Keras based on the Classification task
Word embedding are a type of word representation that allows words with similar meaning to have a similar representation


The Dataset of 25,000 movie reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been preprocessed,
and each review is encoded as a sequence of word indexes (integers). For convenience, the words are indexed by their
frequency in the dataset, meaning the for that has index 1 is the most frequent word. Use the first 20 words from each review to
speed up training, using a max vocab size of 10,000.
As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word.


