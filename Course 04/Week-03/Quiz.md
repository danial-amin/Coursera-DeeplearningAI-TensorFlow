Question 1<br>
If X is the standard notation for the input to an RNN, what are the standard notations for the outputs?<br>
Y<br>
H<br>
<ins>**Y(hat) and H**</ins><br>
H(hat) and Y<br>
Question 2<br>
What is a sequence to vector if an RNN has 30 cells numbered 0 to 29<br>
The Y(hat) for the first cell<br>
<ins>**The Y(hat) for the last cell**</ins><br>
The total Y(hat) for all cells<br>
The average Y(hat) for all 30 cells<br>
Question 3<br>
What does a Lambda layer in a neural network do?<br>
There are no Lambda layers in a neural network<br>
Changes the shape of the input or output data<br>
Pauses training without a callback<br>
<ins>**Allows you to execute arbitrary code while training**</ins><br>
Question 4<br>
What does the axis parameter of tf.expand_dims do?<br>
Defines the dimension index to remove when you expand the tensor<br>
Defines the axis around which to expand the dimensions<br>
<ins>**Defines the dimension index at which you will expand the shape of the tensor **</ins><br>
Defines if the tensor is X or Y<br>
Question 5<br>
A new loss function was introduced in this module, named after a famous statistician. What is it called?<br>
Hyatt loss<br>
Hawking loss<br>
<ins>**Huber loss**</ins><br>
Hubble loss<br>
Question 6<br>
What’s the primary difference between a simple RNN and an LSTM<br>
LSTMs have multiple outputs, RNNs have a single one<br>
In addition to the H output, RNNs have a cell state that runs across all cells <br>
<ins>**In addition to the H output, LSTMs have a cell state that runs across all cells **</ins><br>
LSTMs have a single output, RNNs have multiple<br>
Question 7<br>
If you want to clear out all temporary variables that tensorflow might have from previous sessions, what code do you run?<br>
tf.cache.backend.clear_session()<br>
tf.keras.clear_session<br>
tf.cache.clear_session()<br>
<ins>**tf.keras.backend.clear_session()  **</ins><br>
Question 8<br>
What happens if you define a neural network with these two layers?<br>
tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),<br>
tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(32)),<br>
tf.keras.layers.Dense(1),<br>
Your model will fail because you have the same number of cells in each LSTM<br>
Your model will fail because you need return_sequences=True after each LSTM layer<br>
Your model will compile and run correctly<br>
<ins>**Your model will fail because you need return_sequences=True after the first LSTM layer**</ins><br>
