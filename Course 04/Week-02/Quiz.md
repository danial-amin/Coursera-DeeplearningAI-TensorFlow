Question 1<br>
What is a windowed dataset?<br>
<ins>**A fixed-size subset of a time series **</ins><br>
A consistent set of subsets of a time series<br>
There’s no such thing<br>
The time series aligned to a fixed shape<br>
Question 2<br>
What does ‘drop_remainder=true’ do?<br>
It ensures that the data is all the same shape<br>
It ensures that all rows in the data window are the same length by adding data<br>
<ins>**It ensures that all rows in the data window are the same length by cropping data**</ins><br>
It ensures that all data is used<br>
Question 3<br>
What’s the correct line of code to split an n column window into n-1 columns for features and 1 column for a label<br>
dataset = dataset.map(lambda window: (window[n-1], window[1]))<br>
<ins>**dataset = dataset.map(lambda window: (window[:-1], window[-1:]))**</ins><br>
dataset = dataset.map(lambda window: (window[-1:], window[:-1]))<br>
dataset = dataset.map(lambda window: (window[n], window[1]))<br>
Question 4<br>
What does MSE stand for?<br>
Mean Series error<br>
Mean Slight error<br>
Mean Second error<br>
<ins>**Mean Squared error**</ins><br>
Question 5<br>
What does MAE stand for?<br>
Mean Average Error<br>
Mean Advanced Error<br>
<ins>**Mean Absolute Error**</ins><br>
Mean Active Error<br>
Question 6<br>
If time values are in time[], series values are in series[] and we want to split the series into training and validation at time 1000, what is the correct code?<br>
time_train = time[split_time]<br>
x_train = series[split_time]<br>
time_valid = time[split_time]<br>
x_valid = series[split_time]<br>
time_train = time[split_time]<br>
x_train = series[split_time]<br>
time_valid = time[split_time:]<br>
x_valid = series[split_time:]<br>
<ins>**time_train = time[:split_time]**</ins><br>
<ins>**x_train = series[:split_time]**</ins><br>
<ins>**time_valid = time[split_time:]**</ins><br>
<ins>**x_valid = series[split_time:]**</ins><br>
time_train = time[:split_time]<br>
x_train = series[:split_time]<br>
time_valid = time[split_time]<br>
x_valid = series[split_time]<br>
Question 7<br>
If you want to inspect the learned parameters in a layer after training, what’s a good technique to use?<br>
<ins>**Iterate through the layers dataset of the model to find the layer you want**</ins><br>
Run the model with unit data and inspect the output for that layer<br>
Decompile the model and inspect the parameter set for that layer<br>
Assign a variable to the layer and add it to the model using that variable. Inspect its properties after training<br>
Question 8<br>
How do you set the learning rate of the SGD optimizer? <br>
Use the RateOfLearning property<br>
Use the Rate property <br>
<ins>**Use the lr property**</ins><br>
You can’t set it<br>
Question 9<br>
If you want to amend the learning rate of the optimizer on the fly, after each epoch, what do you do?<br>
Use a LearningRateScheduler and pass it as a parameter to a callback<br>
Callback to a custom function and change the SGD property<br>
<ins>**Use a LearningRateScheduler object in the callbacks namespace and assign that to the callback **</ins><br>
You can’t set it<br>
