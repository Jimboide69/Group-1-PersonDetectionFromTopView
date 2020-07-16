# Group-1-PersonDetectionFromTopView

This is a Keras port of the SSD model architecture, introduced by Wei Liu et al. in the paper [SSD: Single Shot MultiBox Detector](https://arxiv.org/abs/1512.02325), modified to adapt it to the Person Detection from a Top-View Perspective in a retail environment.

The repository currently provides the following network architectures:
* SSD300-VGG16: [`keras_vgg16_ssd300.py`](models/keras_ssd300.py)
* SSD300-ResNet50: [`keras_resnet50_ssd300.py`](models/keras_resnet50_ssd300.py)
* SSD512-VGG16: [`keras_vgg16_ssd512.py`](models/keras_ssd512.py)
* SSD512-ResNet50: [`keras_resnet50_ssd512.py`](models/keras_resnet50_ssd512.py)
* SSD7: [`keras_ssd7.py`](models/keras_ssd7.py) - a smaller 7-layer version

The notebooks in this repository are used to train and evaluate the various architectures of the SSD used in the Computer Vision and Deep Learning project. The few things to change are the paths to any weights and folders containing the dataset.

Link to Download the Dataset:
https://drive.google.com/file/d/1mixMS8lWmjqeiCQuK7pHdw3M47tMohQj/view?usp=sharing
