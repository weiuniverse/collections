# packages_collection
packages of python,  computer vision, machine learning, deep learning and others

## 常用工具
### [Anaconda](https://anaconda.org/)
Python 科学计算包，包含 numpy,scipy,matplotlib,jupyter notebook 等python科学计算的常用工具。
#### conda
conda是一个python packages的管理工具，与pip类似。但是本身自带多版本管理的功能，对多环境的开发者较为方便。

参考：
[Anaconda多环境多版本python配置指导](https://www.jianshu.com/p/d2e15200ee9b)

#### 其他衍生品
[miniconda](https://conda.io/miniconda.html):简化版的anaconda

[bioconda](https://bioconda.github.io/):用于生物计算版本

### [jupyter notebook](http://jupyter.org/)
Jupyter Notebook是一个交互式笔记本，支持运行 40 多种编程语言。

#### 优点:

    1.可以再浏览器中进行编程，并且直接显示结果，适合用来演示程序结果，以及数据科学的相关工作。
    2.可以在程序中加入markdown，对程序进行解释。
    3.结果可以导出为 slide,markdown等方便演示的格式。

#### 入门资料：
[Jupyter Notebook 快速入门上](http://codingpy.com/article/getting-started-with-jupyter-notebook-part-1/)

[Jupyter Notebook 快速入门下](http://codingpy.com/article/getting-started-with-jupyter-notebook-part-2/)

## 机器学习工具包
### [sklearn](http://sklearn.lzjqsdd.com/index.html)
机器学习工具包，包含数据预处理功能，并且集合了常用的机器学习方法，如 pca,svm,adaboost 等。
使用pip安装。
#### 相关资料
[中文文档](http://sklearn.lzjqsdd.com/index.html)

### [xgboost](http://xgboost.apachecn.org/cn/latest/)
集成学习工具包

### [LightGBM](https://github.com/Microsoft/LightGBM)
由微软开发的集成学习包

## 深度学习
### [tensorflow](https://www.tensorflow.org/get_started/)
google 开源的深度学习框架，可以在windows,macos,linux,Android平台上使用。
使用pip安装。

教程:

[morvan python 视频教程](https://morvanzhou.github.io/tutorials/machine-learning/tensorflow/)

[中文社区](http://www.tensorfly.cn/)

### [tfgan](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/gan)
基于tensorflow平台的轻量级 生成对抗网络开发工具。

### [keras](https://keras.io/)
基于tensorflow,theano,CNTK的深度学习框架。比tensorflow等封装的更加完整，上手更加容易，但是灵活性稍差。
使用pip安装。
### [magenta](https://github.com/tensorflow/magenta)
基于tensorflow的一个工具包，用于生成艺术作品如音乐画作等。
使用pip安装。
## 计算机视觉工具包
### [opencv](https://opencv.org/)
#### 安装
对于 python,直接使用 pip install opencv.

如果安装失败，可以到[pypi](https://pypi.python.org/pypi/opencv-python)上下载相对应的版本在本地用pip安装。

#### 教程
[opencv tutorial](https://github.com/weiuniverse/cv_tutorial):正在更新中...

[learn opencv](http://www.learnopencv.com/)

[opencv 中文开发文档](http://www.linuxidc.com/Linux/2015-08/121400.htm):旧版

[opencv 开发教程](https://github.com/makelove/OpenCV-Python-Tutorial)

[opencv python 开发文档](https://docs.opencv.org/3.3.0/d6/d00/tutorial_py_root.html)

### dlib
基于深度学习的人脸探测，人脸特征点探测工具包。易于使用。
使用 pip 安装。

#### 可参考项目

[添加圣诞帽](https://github.com/weiuniverse/add_chrismas_hat)

### [face_recognition](https://github.com/ageitgey/face_recognition)
简单的人脸识别库.可使用pip 安装。

#### 可参考项目
[facetimes](https://github.com/weiuniverse/facetimes/blob/master/project/face_detection_v3.py)
