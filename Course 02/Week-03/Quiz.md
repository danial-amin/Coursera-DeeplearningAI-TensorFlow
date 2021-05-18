Question 1<br>
If I put a dropout parameter of 0.2, how many nodes will I lose?<br>
2% of them<br>
<ins>**20% of them**</ins><br>
20% of the untrained ones<br>
2% of the untrained ones<br>

Question 2<br>
Why is transfer learning useful?<br>
Because I can use all of the data from the original training set<br>
<ins>**Because I can use the features that were learned from large datasets that I may not have access to**</ins><br>
Because I can use all of the data from the original validation set<br>
Because I can use the validation metadata from large datasets that I may not have access to<br>

Question 3<br>
How did you lock or freeze a layer from retraining?<br>
tf.freeze(layer)<br>
tf.layer.frozen = true<br>
tf.layer.locked = true<br>
<ins>**layer.trainable = false**</ins><br>

Question 4<br>
How do you change the number of classes the model can classify when using transfer learning? (i.e. the original model handled 1000 classes, but yours handles just 2)?<br>
<ins>**When you add your DNN at the bottom of the network, you specify your output layer with the number of classes you want**</ins><br>
Ignore all the classes above yours (i.e. Numbers 2 onwards if I'm just classing 2)<br>
Use all classes but set their weights to 0<br>
Use dropouts to eliminate the unwanted classes<br>

Question 5<br>
Can you use Image Augmentation with Transfer Learning Models?<br>
No, because you are using pre-set features<br>
<ins>**Yes, because you are adding new layers at the bottom of the network, and you can use image augmentation when training these**</ins><br>

Question 6<br>
Why do dropouts help avoid overfitting?<br>
Having less neurons speeds up training<br>
<ins>**Because neighbor neurons can have similar weights, and thus can skew the final training **</ins><br>

Question 7<br>
What would the symptom of a Dropout rate being set too high?<br>
Training time would increase due to the extra calculations being required for higher dropout<br>
<ins>**The network would lose specialization to the effect that it would be inefficient or ineffective at learning, driving accuracy down**</ins><br>

Question 8<br>
Which is the correct line of code for adding Dropout of 20% of neurons using TensorFlow<br>
tf.keras.layers.Dropout(20)<br>
tf.keras.layers.DropoutNeurons(20)<br>
tf.keras.layers.DropoutNeurons(0.2)<br>
<ins>**tf.keras.layers.Dropout(0.2)**</ins><br>
