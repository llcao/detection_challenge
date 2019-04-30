# Problem 
[A recent work by Amir Rosenfeld, Richard Zemel, John K. Tsotsos](https://arxiv.org/abs/1808.03305) shows that state-of-the art object detectors will fail by replacing image sub-regions by another sub-image that contains a trained object. Their work has a funny name "Elephant in the room". At [Amir's website](https://sites.google.com/view/amirrosenfeld), we can find a number of pictures which failed TensorFlow detectors.

Following their work, we want to prepare a more comprehensive datasets to challenge the state of the art detectors.

# Dataset
We will modify the [coco dataset](http://cocodataset.org/) to generate these challenging photos

# Detectors
We will focus on the following two detector frameworks.
1. [Tensorflow Detection APIs](https://github.com/tensorflow/models/tree/master/research/object_detection)
2. [Detectron on Caffe2 or Pytorch](https://github.com/facebookresearch/Detectron/)

# todos (04/30)

1. (mehul1107@) will pytorch detectors and see whether they fail in the same images as Tensorflow Object Detector API. You may try to use [Amir's examples](https://drive.google.com/drive/folders/112tOxY5jO-3VHDy0ddJjrGHDHfT7SynQ?usp=sharing) to test.

2. (sid0913@) strategy 1: place the incoming objects on the border the object boxes in coco set: laptop, TV, human, (maybe faces)
