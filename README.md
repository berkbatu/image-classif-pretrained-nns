## Image Classification Examples with Pretrained Neural Nets

In this repo, I'm trying out a Neural Nets to try and classify several images. The variety of NNs and methods will increase over time. For now I'm using models from Keras, such as VGG16, VGG19 which have high accuracy in the ImageNet dataset.

### Getting Started

I've used Google Colab and Jupyter notebook on this project. 

### Models and Data Used

Data: ImageNet is a dataset of over 15 million labeled high-resolution images belonging to roughly 22,000 categories. The images were collected from the web and labeled by human labelers using Amazon’s Mechanical Turk crowd-sourcing tool. Starting in 2010, as part of the Pascal Visual Object Challenge, an annual competition called the ImageNet Large-Scale Visual Recognition Challenge (ILSVRC) has been held. ILSVRC uses a subset of ImageNet with roughly 1000 images in each of 1000 categories. At all, there are roughly 1.2 million training images, 50,000 validation images, and 150,000 testing images. ImageNet consists of variable-resolution images. Therefore, the images have been down-sampled to a fixed resolution of 256×256. Given a rectangular image, the image is rescaled and cropped out the central 256×256 patch from the resulting image.

### Libraries Used 

```
keras
tensorflow
numpy
```

## Further Works
As a future work, I will try to create and train my own Keras model to classify images from 7 or 8 different categories.
