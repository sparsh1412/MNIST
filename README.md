# MNIST

This Code recognizes hand written digits.
The dataset used is MNIST.
It has 55,000 training images and 10,000 tesing images.
Each Image has a correct label associated with it.

I have use a Convolutional Neural Network (CNN) which has the following architecture:

1. An input image of 28 x 28 pixels.
2. Convolution layer 1 with 32 units(or nodes) each having stride = 1, k = 5, and padding = "SAME".
3. Maxpooling layer with k = 2.
3. Convolution layer 1 with 64 units(or nodes) each having stride = 1, k = 5, and padding = "SAME". 
4. Maxpooling layer with k = 2.
5. Hidden Layer (or Dense Layer) with 1024 units.
6. Output layer with 10 units that determine the digit (range 0-9) in the image.

The network recognized 9864 images (out of 10,000 testing images) correctly giving an accuracy of 98.64%.
