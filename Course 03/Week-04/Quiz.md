Question 1<br>
What is the name of the method used to tokenize a list of sentences?<br>
<ins>**fit_on_texts(sentences)**</ins><br>
tokenize_on_text(sentences)<br>
fit_to_text(sentences)<br>
tokenize(sentences)<br>
Question 2<br>
If a sentence has 120 tokens in it, and a Conv1D with 128 filters with a Kernal size of 5 is passed over it, what’s the output shape?<br>
<ins>**(None, 116, 128)**</ins><br>
(None, 116, 124)<br>
(None, 120, 124)<br>
(None, 120, 128)<br>
Question 3<br>
What is the purpose of the embedding dimension?<br>
It is the number of dimensions required to encode every word in the corpus<br>
It is the number of letters in the word, denoting the size of the encoding<br>
It is the number of words to encode in the embedding<br>
<ins>**It is the number of dimensions for the vector representing the word encoding**</ins><br>
Question 4<br>
IMDB Reviews are either positive or negative. What type of loss function should be used in this scenario?<br>
<ins>**Binary Gradient descent**</ins><br>
Categorical crossentropy<br>
Binary crossentropy<br>
Adam<br>
Question 5<br>
If you have a number of sequences of different lengths, how do you ensure that they are understood when fed into a neural network?<br>
Process them on the input layer of the Neural Network using the pad_sequences property<br>
<ins>**Use the pad_sequences object from the tensorflow.keras.preprocessing.sequence namespace**</ins><br>
Make sure that they are all the same length using the pad_sequences method of the tokenizer<br>
Specify the input layer of the Neural Network to expect different sizes with dynamic_length<br>
Question 6<br>
When predicting words to generate poetry, the more words predicted the more likely it will end up gibberish. Why?<br>
Because the probability of prediction compounds, and thus increases overall<br>
Because you are more likely to hit words not in the training set<br>
It doesn’t, the likelihood of gibberish doesn’t change<br>
<ins>**Because the probability that each word matches an existing phrase goes down the more words you create**</ins><br>
Question 7<br>
What is a major drawback of word-based training for text generation instead of character-based generation?<br>
Word based generation is more accurate because there is a larger body of words to draw from<br>
Character based generation is more accurate because there are less characters to predict<br>
There is no major drawback, it’s always better to do word-based training<br>
<ins>**Because there are far more words in a typical corpus than characters, it is much more memory intensive**</ins><br>
Question 8<br>
How does an LSTM help understand meaning when words that qualify each other aren’t necessarily beside each other in a sentence?<br>
They don’t<br>
<ins>**Values from earlier words can be carried to later ones via a cell state**</ins><br>
They load all words into a cell state<br>
They shuffle the words randomly<br>
