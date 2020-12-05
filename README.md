# SRGAN

Single Image Super-Resolution Using a Generative Adversarial Network.

COCO dataset 2017, being reshaped to 320x240 was used for training, but not exclusive to this dataset. Anyone can add dataset with porper path define.

This inspired and adapted from the medium article https://medium.com/@birla.deepak26/single-image-super-resolution-using-gans-keras-aca310f33112, and the mentioned git repo in the article, which I tried to compile to a Jupyter notebook.

You will need the following to run the above:
Python 3.5.4,
tensorflow 1.11.0,
keras 2.2.4,
numpy 1.10.4,
matplotlib, skimage, scipy


# References:

Paper:
Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network: https://arxiv.org/pdf/1609.04802.pdf,
Perceptual Losses for Real-Time Style Transfer and Super-Resolution: https://cs.stanford.edu/people/jcjohns/papers/eccv16/JohnsonECCV16.pdf

Projects doing the same thing:
https://github.com/MathiasGruber/SRGAN-Keras,
https://github.com/titu1994/Super-Resolution-using-Generative-Adversarial-Networks,
https://github.com/eriklindernoren/Keras-GAN/tree/master/srgan,
https://github.com/brade31919/SRGAN-tensorflow,
https://github.com/tensorlayer/srgan
 
Help on GANS:
https://github.com/eriklindernoren/Keras-GAN (Various GANS implemented in Keras),
https://github.com/JGuillaumin/SuperResGAN-keras,
https://oshearesearch.com/index.php/2016/07/01/mnist-generative-adversarial-model-in-keras/

VGG loss help:
https://blog.sicara.com/keras-generative-adversarial-networks-image-deblurring-45e3ab6977b5

SubpixelConv2D(Deconvolution) help:
Real-Time Single Image and Video Super-Resolution Using an Efficient Sub-Pixel Convolutional Neural Network: https://arxiv.org/abs/1609.05158,
https://github.com/twairball/keras-subpixel-conv

Improved Techniques for Training GANs:
https://arxiv.org/abs/1606.03498

references copied from https://github.com/deepak112/Keras-SRGAN

