## CNN_TensorFlow_Dataset_Flowers
### TensorFlow Datasets: tf_flowers (https://www.tensorflow.org/datasets/catalog/tf_flowers)

The flowers dataset consists of images of flowers with **5 possible class labels.**
The flowers dataset consists of examples which are labeled images of flowers. 
Each example contains a JPEG flower image and the class label: what type of flower it is. 


For classifying images, a particular type of deep neural network, called a convolutional neural network has proved to be particularly powerful.
However, modern convolutional neural networks have millions of parameters. 
Training them from scratch requires a lot of labeled training data and a lot of computing power (hundreds of GPU-hours or more).
We only have about three thousand labeled photos and want to spend much less time.

We had tried to build a CNN from scratch. 
Data augmentation is used: a technique to increase the diversity of your training set by applying random (but realistic) transformations, such as image rotation.
Various techniques used to improve model performance:
### 1. kernel initializers = GlorotUniform
### 2. Batch Normalization
### 3. Dropout
### 4. Reduce LR On Plateau

Model acheives **95% training** and **74% validation accuaracy.**


