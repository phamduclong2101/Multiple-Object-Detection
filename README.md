# Multiple Detection - SSD-EfficientDet
<br> <img width="1100" alt="RGB" src="https://github.com/phamduclong2101/Multiple-Detection/blob/de9cca8cb689dc8ae05e45725cce2812c9b2dc41/assets/ssd_architecture.png">


* Learn about *EfficientDet* and separable depthwise convolutions.
* The SSD (Single Shot Detection) architecture used for object detection
* Use pretrained TensorFlow object detection inference models to detect objects
* Use different architectures and weigh the tradeoffs.

Open the notebook and work through it!

### Requirements

Install environment with [Anaconda](https://www.continuum.io/downloads):

```sh
conda env create -f environment.yml
```

Change TensorFlow pip installation from `tensorflow-gpu` to `tensorflow` if you don't have a GPU available.

The environment should be listed via `conda info --envs`:

```sh
# conda environments:
#
carnd-advdl-odlab        /usr/local/anaconda3/envs/carnd-advdl-odlab
root                  *  /usr/local/anaconda3
```

Further documentation on [working with Anaconda environments](https://conda.io/docs/using/envs.html#managing-environments). 

### Dowload Dataset:
* Installing Python, PyCharm, Git to Computer.
* Download the source dataset from [VisDrone_DataSet](http://aiskyeye.com/home/).

### Training results
<br> <img width="600" alt="RGB" src="https://github.com/phamduclong2101/Multiple-Detection/blob/af5aee9eb1d6f8527be3fe30e5955e3714408da3/Results/re_metrics.png">

### Train and validation of loss metrics
<br> <img width="1100" alt="RGB" src="https://github.com/phamduclong2101/Multiple-Detection/blob/af5aee9eb1d6f8527be3fe30e5955e3714408da3/Results/b.png">
<br> <img width="1100" alt="RGB" src="https://github.com/phamduclong2101/Multiple-Detection/blob/af5aee9eb1d6f8527be3fe30e5955e3714408da3/Results/c.png">

### Samples output
<br> <img width="1100" alt="RGB" src="https://github.com/phamduclong2101/Multiple-Detection/blob/af5aee9eb1d6f8527be3fe30e5955e3714408da3/assets/1.png">
<br> <img width="1100" alt="RGB" src="https://github.com/phamduclong2101/Multiple-Detection/blob/af5aee9eb1d6f8527be3fe30e5955e3714408da3/assets/2.png">

### Resources

* TensorFlow object detection [model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md)


### Future Work

* Experiment with Fast-R-CNN, Detr, Yolov8 and compare its performance with SSD


### **Technologies used**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)


### **Tools used**
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

<!-- Tools Used -->
[PyCharm]: https://code.visualstudio.com/
[git]: https://git-scm.com/
[github]: https://github.com/
[python]: https://www.python.org/
[sklearn]: https://scikit-learn.org/stable/

### Authors

Pham Duc Long


### Acknowledgments
* "https://arxiv.org/abs/1911.09070"
* "https://arxiv.org/abs/1512.02325"
