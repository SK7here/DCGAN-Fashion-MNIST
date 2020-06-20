# DCGAN-Fashion-MNIST
<b>Fashion MNIST</b> dataset is directly downloaded from <b>tf.keras.datasets</b><br>
Composed of <b>60,000 training images</b> and <b>10,000 test images</b><br>
Dimension of each image is <b>28x28</b><br>

Random Gaussian noise is added to make sure we get <b>realistic images</b> and not the <b>exact images</b><br>

To improve DCGAN model performance (use GPU/Colab for these cases)
1. Increase the number of epochs
2. Increase the number of layers for Generator and Discriminator

To use custom images of different dimensions
1. Make changes in input size of Discriminator
2. Modify layers in both Generator and Discriminator accordingly
