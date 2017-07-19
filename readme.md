# ICCV 2017
-------

This code implements the algorithm introduced in:

* Jinsong Zhang and Jean-François Lalonde, Learning High Dynamic Range from Outdoor Panoramas, International Conference on Computer Vision (ICCV), 2017.

This code takes as input a single LDR omnidirectional panorama, and converts it to HDR automatically.

For more details, please see our project webpage: http://vision.gel.ulaval.ca/~jflalonde/projects/learningHDR.

*Important*: if you use this code, please cite the paper above!


## Getting started
Execute the `ldr2hdr.py` to generate HDR image.

Download the data and model from our [project webpage](http://vision.gel.ulaval.ca/~jflalonde/projects/learningHDR.)
The provided data contains all the data we are using in our training and test. To train the domain adaptation model, you may need to download the [SUN360 dataset](http://vision.princeton.edu/projects/2012/SUN360/).

The images have been aligned by centering the sun. Place the model in `./model' folder.

## Requirements
Our model is trained with [TensorFlow](https://www.tensorflow.org/); and [OpenEXR](http://www.openexr.com/) is used to write HDR images.
