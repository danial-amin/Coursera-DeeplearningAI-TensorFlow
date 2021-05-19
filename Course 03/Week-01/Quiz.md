Question 1<br>
What is the name of the object used to tokenize sentences?<br>
CharacterTokenizer<br>
TextTokenizer<br>
<ins>**Tokenizer**</ins><br>
WordTokenizer<br>
Question 2<br>
What is the name of the method used to tokenize a list of sentences?<br>
<ins>**fit_on_texts(sentences)**</ins><br>
tokenize_on_text(sentences)<br>
fit_to_text(sentences)<br>
tokenize(sentences)<br>
Question 3<br>
Once you have the corpus tokenized, what’s the method used to encode a list of sentences to use those tokens?<br>
texts_to_tokens(sentences)<br>
text_to_tokens(sentences)<br>
text_to_sequences(sentences)<br>
<ins>**texts_to_sequences(sentences)**</ins><br>
Question 4<br>
When initializing the tokenizer, how to you specify a token to use for unknown words?<br>
out_of_vocab=<Token><br>
unknown_token=<Token><br>
<ins>**oov_token=<Token>**</ins><br>
unknown_word=<Token><br>
Question 5<br>
If you don’t use a token for out of vocabulary words, what happens at encoding?<br>
The word isn’t encoded, and the sequencing ends<br>
<ins>**The word isn’t encoded, and is skipped in the sequence**</ins><br>
The word isn’t encoded, and is replaced by a zero in the sequence<br>
The word is replaced by the most common token<br>
Question 6<br>
If you have a number of sequences of different lengths, how do you ensure that they are understood when fed into a neural network?<br>
Process them on the input layer of the Neural Netword using the pad_sequences property<br>
Specify the input layer of the Neural Network to expect different sizes with dynamic_length<br>
Make sure that they are all the same length using the pad_sequences method of the tokenizer<br>
<ins>**Use the pad_sequences object from the tensorflow.keras.preprocessing.sequence namespace**</ins><br>
Question 7<br>
If you have a number of sequences of different length, and call pad_sequences on them, what’s the default result?<br>
Nothing, they’ll remain unchanged<br>
They’ll get cropped to the length of the shortest sequence<br>
They’ll get padded to the length of the longest sequence by adding zeros to the end of shorter ones<br>
<ins>**They’ll get padded to the length of the longest sequence by adding zeros to the beginning of shorter ones**</ins><br>
Question 8<br>
When padding sequences, if you want the padding to be at the end of the sequence, how do you do it?<br>
Call the padding method of the pad_sequences object, passing it ‘post’<br>
Call the padding method of the pad_sequences object, passing it ‘after’<br>
<ins>**Pass padding=’post’ to pad_sequences when initializing it**</ins><br>
Pass padding=’after’ to pad_sequences when initializing it<br>
![image](https://user-images.githubusercontent.com/76213137/118770274-90dfea00-b89a-11eb-8680-8316b0629f34.png)
