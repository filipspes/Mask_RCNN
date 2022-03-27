# Mask R-CNN for Object Detection and Segmentation

This fork of the matterport/mask_rcnn repo was customized to detect fingeprint sweat pores.
I custumized this repo to work with a custom dataset.

This is an implementation of [Mask R-CNN](https://arxiv.org/abs/1703.06870) on Python 3, Keras, and TensorFlow. The model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet50 backbone.

# Getting Started
## Requirements
All required packages are listed in `requirements.txt`. Most of the is inslalled alongside with othre packages.

## Installation
To run this implementation locally do following:

1. `conda create --name=Mask_R-CNN python=3.8`
2. `clone this repository`
3. `cd Mask_RCNN`
4. `conda install -c anaconda tensorflow-gpu`
5. `conda install -c anaconda pillow`
6. `conda install -c anaconda scikit-image`
7. `conda install -c anaconda ipython`
8. `conda install -c conda-forge keras`
9. `conda install -c conda-forge opencv`


## Original repo citation
Use this bibtex to cite this repository:
```
@misc{matterport_maskrcnn_2017,
  title={Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow},
  author={Waleed Abdulla},
  year={2017},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/matterport/Mask_RCNN}},
}
```
