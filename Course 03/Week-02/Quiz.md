Question 1<br>
What is the name of the TensorFlow library containing common data that you can use to train and test neural networks?<br>
TensorFlow Data Libraries<br>
There is no library of common data sets, you have to use your own<br>
TensorFlow Data<br>
<ins>**TensorFlow Datasets**</ins><br>
Question 2<br>
How many reviews are there in the IMDB dataset and how are they split?<br>
60,000 records, 80/20 train/test split<br>
<ins>**50,000 records, 50/50 train/test split**</ins><br>
60,000 records, 50/50 train/test split<br>
50,000 records, 80/20 train/test split<br>
Question 3<br>
How are the labels for the IMDB dataset encoded?<br>
<ins>**Reviews encoded as a number 0-1**</ins><br>
Reviews encoded as a number 1-10<br>
Reviews encoded as a number 1-5<br>
Reviews encoded as a boolean true/false<br>
Question 4<br>
What is the purpose of the embedding dimension?<br>
<ins>**It is the number of dimensions for the vector representing the word encoding**</ins><br>
It is the number of letters in the word, denoting the size of the encoding<br>
It is the number of words to encode in the embedding<br>
It is the number of dimensions required to encode every word in the corpus<br>
Question 5<br>
When tokenizing a corpus, what does the num_words=n parameter do?<br>
<ins>**It specifies the maximum number of words to be tokenized, and picks the most common ‘n’ words**</ins><br>
It errors out if there are more than n distinct words in the corpus<br>
It specifies the maximum number of words to be tokenized, and picks the first ‘n’ words that were tokenized<br>
It specifies the maximum number of words to be tokenized, and stops tokenizing when it reaches n<br>
Question 6<br>
To use word embeddings in TensorFlow, in a sequential layer, what is the name of the class?<br>
tf.keras.layers.Embed<br>
<ins>**tf.keras.layers.Embedding**</ins><br>
tf.keras.layers.WordEmbedding<br>
tf.keras.layers.Word2Vector<br>
Question 7<br>
IMDB Reviews are either positive or negative. What type of loss function should be used in this scenario?<br>
Adam<br>
<ins>**Binary crossentropy**</ins><br>
Binary Gradient descent<br>
Categorical crossentropy<br>
Question 8<br>
When using IMDB Sub Words dataset, our results in classification were poor. Why?<br>
We didn’t train long enough<br>
The sub words make no sense, so can’t be classified<br>
Our neural network didn’t have enough layers<br>
<ins>**Sequence becomes much more important when dealing with subwords, but we’re ignoring word positions**</ins><br>
