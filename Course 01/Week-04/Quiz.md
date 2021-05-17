Question 1<br>
Using Image Generator, how do you label images?<br>
**<ins>It’s based on the directory the image is contained in</ins>**<br>
It’s based on the file name<br>
TensorFlow figures it out from the contents<br>
You have to manually do it<br>

Question 2<br>
What method on the Image Generator is used to normalize the image?<br>
Rescale_image<br>
normalize<br>
**<ins>rescale</ins>**<br>
normalize_image<br>

Question 3<br>
How did we specify the training size for the images?<br>
The training_size parameter on the validation generator<br>
The target_size parameter on the validation generator<br>
The training_size parameter on the training generator<br>
**<ins>The target_size parameter on the training generator</ins>**<br>

Question 4<br>
When we specify the input_shape to be (300, 300, 3), what does that mean?<br>
Every Image will be 300x300 pixels, and there should be 3 Convolutional Layers<br>
**<ins>Every Image will be 300x300 pixels, with 3 bytes to define color</ins>**<br>
There will be 300 images, each size 300, loaded in batches of 3<br>
There will be 300 horses and 300 humans, loaded in batches of 3<br>

Question 5<br>
If your training data is close to 1.000 accuracy, but your validation data isn’t, what’s the risk here?<br>
No risk, that’s a great result<br>
**<ins>You’re overfitting on your training data</ins>**<br>
You’re underfitting on your validation data<br>
You’re overfitting on your validation data<br>

Question 6<br>
Convolutional Neural Networks are better for classifying images like horses and humans because:<br>
In these images, the features may be in different parts of the frame<br>
There’s a wide variety of horses<br>
There’s a wide variety of humans<br>
**<ins>All of the above</ins>**<br>

Question 7<br>
After reducing the size of the images, the training results were different. Why?<br>
**<ins>We removed some convolutions to handle the smaller images</ins>**<br>
There was less information in the images<br>
There was more condensed information in the images<br>
The training was faster<br>