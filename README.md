
**Winning the best student paper award(2nd place) in IW-FCV2018!**

# Sealion detection and classification

This code was used for [NOAA sealion competition](https://www.kaggle.com/c/noaa-fisheries-steller-sea-lion-population-count) which was held in KAGGLE. <br/>Final result is **58th** among 385 participants.

## Citing this code

Detail is described in the [paper](http://vi.kaist.ac.kr/wp-content/uploads/2018/01/iw-fcv2018_final_youngchul.pdf)

```
@inproceedings{IWFCV18sealion,
  title = {Animal Detection in Huge Air-view Images using CNN-based Sliding Window},
  author = {Young-Chul Yoon and Kuk-Jin Yoon},
  booktitle = {International Workshops on Frontiers of Computer Vision},
  year = {2018}
}
```

## Prerequisites

Hardware
```
Nvidia GPU with at least 3GB memory
```
Interpreter and Operating System
```
Python version 2.7 or 3.5
Tested on UBUNTU 16.04 and Windows
```
Dependency
```
tensorflow-gpu
python-opencv
imgaug
numpy
csv
skimage
```
## Installing and demo

You have to download this repository and also pre-trained model.

```
pre-trained model download link : https://drive.google.com/open?id=0Bwaxr_eelTFyS0Vyc2NfajJNb1E
```
You have to depress the 'sealion_count_model.zip' into 'input' directory.

## Running the tests

You can run the control.py (EX. python2 control.py).

The code will show you the detection&classification result on sample images.


## About this code

The detector is applied on image through sliding-window method.
<img src="https://github.com/yyc9268/Sealion_Detection_Classification/blob/master/images/framework1.png" width="600">
<img src="https://github.com/yyc9268/Sealion_Detection_Classification/blob/master/images/framework2.png" width="600">


The detector network is like below. The network is separated into detection part and classification part.
<img src="https://github.com/yyc9268/Sealion_Detection_Classification/blob/master/images/network.png" width="600">


Here are several example results of code.<br/>
<img src="https://github.com/yyc9268/Sealion_Detection_Classification/blob/master/images/results.png" width="400">

## Acknowledgments

This repository will be updated frequently.
