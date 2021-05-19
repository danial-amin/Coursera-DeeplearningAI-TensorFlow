Question 1<br>
The diagram for traditional programming had Rules and Data In, but what came out?<br>
Binary<br>
Bugs<br>
Machine Learning<br>
<ins>**Answers**</ins><br>

Question 2<br>
Why does the DNN for Fashion MNIST have 10 output neurons?<br>
Purely arbitrary<br>
To make it train 10x faster<br>
**<ins>The dataset has 10 classes.</ins>**<br>
To make it classify 10x faster<br>

Question 3<br>
What is a Convolution?<br>
A technique to make images bigger<br>
<ins>**A technique to isolate features in images**</ins><br>
A technique to filter out unwanted images<br>
A technique to make images smaller<br>

Question 4<br>
Applying Convolutions on top of our Deep neural network will have what impact on training:<br>
It will be Slower<br>
There will be no impact<br>
It will be Faster<br>
<ins>**It depends on many factors. It might make your training faster or slower, and a poorly designed Convolutional layer may even be less efficient than a plain DNN!**</ins><br>

Question 5<br>
What method on the Image Generator is used to normalize the image?<br>
Rescale_image<br>
normalize<br>
**<ins>rescale</ins>**<br>
normalize_image<br>

Question 6<br>
When using Image Augmentation with the ImageDataGenerator, what happens to your raw image data on-disk?<br>
It gets overwritten, so be sure to make a backup<br>
**<ins>Nothing</ins>**<br>
A copy is made and the augmentation is done on the copy<br>
A copy is made and the augmentation is done on the original<br>

Question 7<br>
Can you use Image Augmentation with Transfer Learning Models?<br>
No, because you are using pre-set features<br>
<ins>**Yes, because you are adding new layers at the bottom of the network, and you can use image augmentation when training these**</ins><br>

Question 8<br>
When training for multiple classes what is the Class Mode for Image Augmentation?<br>
class_mode='multiple'<br>
class_mode='non_binary'<br>
class_mode='all'<br>
<ins>**class_mode='categorical'**</ins><br>
