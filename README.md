## Group-1-PersonDetectionFromTopView
---
### Overview

This is a Keras port of the SSD model architecture, introduced by Wei Liu et al. in the paper [SSD: Single Shot MultiBox Detector](https://arxiv.org/abs/1512.02325), modified to adapt it to the [Person Detection from Top-View Perspective](Paper.pdf) in a retail environment.

The repository currently provides the following network architectures:
* SSD300-VGG16: [`keras_vgg16_ssd300.py`](models/keras_ssd300.py)
* SSD300-ResNet50: [`keras_resnet50_ssd300.py`](models/keras_resnet50_ssd300.py)
* SSD512-VGG16: [`keras_vgg16_ssd512.py`](models/keras_ssd512.py)
* SSD512-ResNet50: [`keras_resnet50_ssd512.py`](models/keras_resnet50_ssd512.py)
* SSD7: [`keras_ssd7.py`](models/keras_ssd7.py) - a smaller 7-layer version

The notebooks in this repository are used to train and evaluate the various architectures of the SSD used in the Computer Vision and Deep Learning project.

This [presentation](Baldascino-Squarcella.pdf) briefly explains the work done.

### How to use it

This repository provides Jupyter notebook that explain training, inference and evaluation for the various architectures of the SSD used in the Computer Vision and Deep Learning project. The few things to change are the paths to any weights and folders containing the dataset.

How to use a trained model for inference:
* [`ssd300_vgg16_inference.ipynb`](ssd300_vgg16_inference.ipynb)
* [`ssd300__resnet50_inference.ipynb`](ssd300__resnet50_inference.ipynb)
* [`ssd512_vgg16_inference.ipynb`](ssd512_vgg16_inference.ipynb)
* [`ssd512_resnet50_inference.ipynb`](ssd512_resnet50_inference.ipynb)

How to train a model:
* [`ssd300_vgg16_training.ipynb`](ssd300_vgg16_training.ipynb)
* [`ssd300_resnet50_training.ipynb`](ssd300_resnet50_training.ipynb)
* [`ssd512_vgg16_training.ipynb`](ssd512_vgg16_training.ipynb)
* [`ssd512_resnet50_training.ipynb`](ssd512_resnet50_training.ipynb)
* [`ssd7_training.ipynb`](ssd7_vgg16_training.ipynb)

How to evaluate a trained model:
* [`ssd300_vgg16_evaluation.ipynb`](ssd300_vgg16_evaluation.ipynb)
* [`ssd300_resnet50_evaluation.ipynb`](ssd300_resnet50_evaluation.ipynb)
* [`ssd512_vgg16_evaluation.ipynb`](ssd512_vgg16_evaluation.ipynb)
* [`ssd512_resnet60_evaluation.ipynb`](ssd512_resnet60_evaluation.ipynb)

Link to Download the weights for all the models trained on CV&DL Dataset:

  * [Weights of SSD7/SSD300/SSD512](https://mega.nz/file/PMJG2Coa#HPIxOnqHbMUotlb-uJa8SuVWd-mpOd9p2jUtrBtUHbg) (.zip, 24.16GB )

Link to Download the Dataset:

  * [CV&DL Dataset](https://drive.google.com/file/d/1mixMS8lWmjqeiCQuK7pHdw3M47tMohQj/view?usp=sharing) (.zip, 1.92GB )
