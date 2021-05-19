
Question 1<br>
What does flow_from_directory give you on the ImageGenerator?<br>
The ability to easily load images for training<br>
The ability to pick the size of training images<br>
The ability to automatically label images based on their directory name<br>
<ins>**All of the above**</ins><br>

Question 2<br>
If my Image is sized 150x150, and I pass a 3x3 Convolution over it, what size is the resulting image?<br>
150x150<br>
<ins>**148x148**</ins><br>
153x153<br>
450x450<br>

Question 3<br>
If my data is sized 150x150, and I use Pooling of size 2x2, what size will the resulting image be?<br>
**<ins>75x75</ins>**<br>
300x300<br>
149x149<br>
150x150<br>

Question 4<br>
If I want to view the history of my training, how can I access it?<br>
Pass the parameter ‘history=true’ to the model.fit<br>
Download the model and inspect it<br>
**<ins>Create a variable ‘history’ and assign it to the return of model.fit or model.fit_generator</ins>**<br>
Use a model.fit_generator<br>

Question 5<br>
What’s the name of the API that allows you to inspect the impact of convolutions on the images?<br>
**<ins>The model.layers API</ins>**<br>
The model.images API<br>
The model.convolutions API<br>
The model.pools API<br>

Question 6<br>
When exploring the graphs, the loss levelled out at about .75 after 2 epochs, but the accuracy climbed close to 1.0 after 15 epochs. What's the significance of this?<br>
There was no point training after 2 epochs, as we overfit to the validation data<br>
A bigger training set would give us better validation accuracy<br>
A bigger validation set would give us better training accuracy<br>
**<ins>There was no point training after 2 epochs, as we overfit to the training data</ins>**<br>

Question 7<br>
Why is the validation accuracy a better indicator of model performance than training accuracy?<br>
It isn't, they're equally valuable<br>
There's no relationship between them<br>
<ins>**The validation accuracy is based on images that the model hasn't been trained with, and thus a better indicator of how the model will perform with new images.**</ins><br>
The validation dataset is smaller, and thus less accurate at measuring accuracy, so its performance isn't as important<br>

Question 8<br>
Why is overfitting more likely to occur on smaller datasets?<br>
Because in a smaller dataset, your validation data is more likely to look like your training data<br>
Because there isn't enough data to activate all the convolutions or neurons<br>
<ins>**Because there's less likelihood of all possible features being encountered in the training process.**</ins><br>
Because with less data, the training will take place more quickly, and some features may be missed<br>
