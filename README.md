 Dogs Vs Cats Classification
 ============
 Given an input image, predict which of them it is. Essentially a binary image classification task.
 
 Approach
 ---------
 <li>Resize the images to size 64x64 and then convert them from RGB to grayscale.</li>
 <li>Create a six layer Convolutional Network with two additional fully connected layers.</li>
 <li>Used the Adam optimizer to improve training speed.</li>
 
 Architecture
 -------------
 <li>6 Convolutional Layers were created</li>
 <li>Each layer had the combination: [Convolution Filter->ReLu->Max Pooling].</li>
 <li>Each Convolution Filter was of size 3x3.</li>
 <li>Filter depths of 32 and 64 was used in alternate layers.</li>
 <li>Filter stride used is 1.</li>
 <li>Pooling window of size 2x2 was used with stride of 2.</li>
 <li>Two fully connected layers of size 1024 and 2 was used.</li>
 
 Results
 --------
 <li>Maximum mini-batch accuracy of 87.5% was achieved.</li>
 <li>Validation accuracy on 500 images of the test set was 74.6% indicating the model was slightly overfit.</li>
 <li>Example of a prediction:</li>
 
 ##Libraries and Packages used
 
 *TensorFlow.
 *Numpy.
 *OpenCV. 
 
