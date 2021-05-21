Question 1<br>
Why does sequence make a large difference when determining semantics of language?<br>
It doesn’t<br>
<ins>**Because the order in which words appear dictate their impact on the meaning of the sentence**</ins><br>
Because the order in which words appear dictate their meaning<br>
Because the order of words doesn’t matter<br>
Question 2<br>
How do Recurrent Neural Networks help you understand the impact of sequence on meaning?<br>
They look at the whole sentence at a time<br>
They shuffle the words evenly<br>
<ins>**They carry meaning from one cell to the next**</ins><br>
They don’t<br>
Question 3<br>
How does an LSTM help understand meaning when words that qualify each other aren’t necessarily beside each other in a sentence?<br>
They don’t<br>
They load all words into a cell state<br>
They shuffle the words randomly<br>
<ins>**Values from earlier words can be carried to later ones via a cell state**</ins><br>
Question 4<br>
What keras layer type allows LSTMs to look forward and backward in a sentence?<br>
Bilateral<br>
Bothdirection<br>
<ins>**Bidirectional**</ins><br>
Unilateral<br>
Question 5<br>
What’s the output shape of a bidirectional LSTM layer with 64 units?<br>
<ins>**(None, 128)**</ins><br>
(128,1)<br>
(None, 64)<br>
(128,None)<br>
Question 6<br>
When stacking LSTMs, how do you instruct an LSTM to feed the next one in the sequence?<br>
<ins>**Ensure that return_sequences is set to True only on units that feed to another LSTM**</ins><br>
Ensure that they have the same number of units<br>
Ensure that return_sequences is set to True on all units<br>
Do nothing, TensorFlow handles this automatically<br>
Question 7<br>
If a sentence has 120 tokens in it, and a Conv1D with 128 filters with a Kernal size of 5 is passed over it, what’s the output shape?<br>
(None, 120, 128)<br>
<ins>**(None, 116, 128)**</ins><br>
(None, 116, 124)<br>
(None, 120, 124)<br>
Question 8<br>
What’s the best way to avoid overfitting in NLP datasets?<br>
Use LSTMs<br>
Use GRUs<br>
Use Conv1D<br>
<ins>**None of the above**</ins><br>
