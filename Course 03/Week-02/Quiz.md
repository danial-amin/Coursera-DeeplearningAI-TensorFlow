Question No.01<br>
How do you use Image Augmentation in TensorFlow?<br>
With the keras.augment API<br>
You have to write a plugin to extend tf.layers<br>
With the tf.augment API<br>
**<ins>Using parameters to the ImageDataGenerator</ins>**<br>

Question 2<br>
Question 2
If my training data only has people facing left, but I want to classify people facing right, how would I avoid overfitting?<br>
Use the ‘flip_vertical’ parameter around the Y axis<br>
Use the ‘flip’ parameter<br>
Use the ‘flip’ parameter and set ‘horizontal’<br>
**<ins>Use the ‘horizontal_flip’ parameter</ins>**<br>

Question 3<br>
When training with augmentation, you noticed that the training is a little slower. Why?<br>
Because the training is making more mistakes<br>
Because the augmented data is bigger<br>
**<ins>Because the image processing takes cycles</ins>**<br>
Because there is more data to train on<br>

Question 4<br>
What does the fill_mode parameter do?<br>
There is no fill_mode parameter<br>
It creates random noise in the image<br>
**<ins>It attempts to recreate lost information after a transformation like a shear</ins>**<br>
It masks the background of an image<br>

Question 5<br>
When using Image Augmentation with the ImageDataGenerator, what happens to your raw image data on-disk?<br>
It gets overwritten, so be sure to make a backup<br>
**<ins>Nothing, all augmentation is done in-memory</ins>**<br>
A copy is made and the augmentation is done on the copy<br>
It gets deleted<br>

Question 6<br>
How does Image Augmentation help solve overfitting?<br>
**<ins>It manipulates the training set to generate more scenarios for features in the imagesa</ins>**<br>
It slows down the training process<br>
It manipulates the validation set to generate more scenarios for features in the images<br>
It automatically fits features to images by finding them through image processing techniques<br>

Question 7<br>
When using Image Augmentation my training gets?<br>
Faster<br>
Much Faster<br>
Stays the Same<br>
**<ins>Slower</ins>**<br>

Question 8<br>
Using Image Augmentation effectively simulates having a larger data set for training.<br>
False<br>
**<ins>True</ins>**<br>
