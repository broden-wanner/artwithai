# Style Transfer with Deep Neural Networks
With this project, I endeavored to apply my knowledge of machine learning to some creative end.
It is a python implementation of the paper <a target="_blank" href="https://arxiv.org/pdf/1508.06576.pdf">"A Neural Algorithm of Artistic Style"</a>
by Gayts et al. The system uses feature representations of images in a neural network to separate and recombine the content of one
image with style of another image. One impressive aspect of this technique is that no new network training is required — 
pre-trained weights (e.g. from ImageNet) work quite well. In essence, a loss function is devised which accounts for the content of
an image and the style of another image, and the script finds the image that minimizes this loss function.
Uses Keras with Tensorflow backend.

Examples:
!(https://github.com/broden-wanner/artwithai/blob/master/initial_images/french_horn.jpg) + !(https://github.com/broden-wanner/artwithai/blob/master/initial_images/starry_night.jpg)  !(https://github.com/broden-wanner/artwithai/blob/master/output_horn_and_starry_night/collected_images.gif)
