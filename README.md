# ImageClassificationAndObjectRecognition

I trained three different convolutional neural nets for use in colorizing images in the CIFAR-10 dataset. The first used nearest neighbors to increase dimension, the second used transposed convolutions, and the third used transposed convolutions as well as skip connections (based on a paper, see below). An image is attached showing the three architectures visaulized. Note that in the image, BS, NIC, NF, and NC are hyperparameters denoting the bath size, number of input color categories, number of filters, and number of output color categories respectively.


Unet reference: 

Olaf Ronneberger, Philipp Fischer, and Thomas Brox. U-net: Convolutional networks for biomedi- cal image segmentation. In International Conference on Medical image computing and computer- assisted intervention, pages 234–241. Springer, 2015.
