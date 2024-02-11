# About

1. This tutorial focuses on the task of image segmentation, using a modified [U-Net](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/).

2. In an image classification task, the network assigns a label (or class) to each input image. However, suppose you want to know the shape of that object, which pixel belongs to which object, etc. In this case, you need to assign a class to each pixel of the image—this task is known as segmentation

3. This tutorial uses the [Oxford-IIIT Pet Dataset (Parkhi et al, 2012)](https://www.robots.ox.ac.uk/%7Evgg/data/pets/). The dataset consists of images of 37 pet breeds, with 200 images per breed (~100 each in the training and test splits). Each image includes the corresponding labels, and pixel-wise masks. The masks are class-labels for each pixel. Each pixel is given one of three categories:

        Class 1: Pixel belonging to the pet.
        Class 2: Pixel bordering the pet.
        Class 3: None of the above/a surrounding pixel.

## Acknowledgement

[Image Segmentation](https://www.tensorflow.org/tutorials/images/segmentation) tutorial at tensorflow.
