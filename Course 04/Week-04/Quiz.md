Question 1<br>
How do you add a 1 dimensional convolution to your model for predicting time series data?<br>
Use a Convolution1D layer type<br>
Use a 1DConv layer type<br>
Use a 1DConvolution layer type<br>
<ins>**Use a Conv1D layer type**</ins><br>
Question 2<br>
What’s the input shape for a univariate time series to a Conv1D? <br>
[1, None]<br>
[1]<br>
<ins>**[None, 1]**</ins><br>
[]<br>
Question 3<br>
You used a sunspots dataset that was stored in CSV. What’s the name of the Python library used to read CSVs?<br>
PyCSV<br>
PyFiles<br>
<ins>**CSV**</ins><br>
CommaSeparatedValues<br>
Question 4<br>
If your CSV file has a header that you don’t want to read into your dataset, what do you execute before iterating through the file using a ‘reader’ object?<br>
reader.next<br>
<ins>**next(reader)**</ins><br>
reader.ignore_header()<br>
reader.read(next)<br>
Question 5<br>
When you read a row from a reader and want to cast column 2 to another data type, for example, a float, what’s the correct syntax?<br>
float f = row[2].read()<br>
<ins>**float(row[2]) **</ins><br>
Convert.toFloat(row[2])<br>
You can’t. It needs to be read into a buffer and a new float instantiated from the buffer<br>
Question 6<br>
What was the sunspot seasonality?<br>
22 years<br>
11 years<br>
<ins>**11 or 22 years depending on who you ask**</ins><br>
4 times a year<br>
Question 7<br>
After studying this course, what neural network type do you think is best for predicting time series like our sunspots dataset?<br>
DNN<br>
Convolutions<br>
RNN / LSTM<br>
<ins>**A combination of all of the above**</ins><br>
Question 8<br>
Why is MAE a good analytic for measuring accuracy of predictions for time series?<br>
It biases towards small errors<br>
It punishes larger errors <br>
<ins>**It doesn’t heavily punish larger errors like square errors do**</ins><br>
It only counts positive errors<br>
