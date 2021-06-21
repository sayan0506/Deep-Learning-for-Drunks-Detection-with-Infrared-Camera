# Deep-Learning-for-Drunks-Detection-with-Infrared-Camera
Deep Learning for Drunks Detection with Infrared Camera Keras implementation


## **Problem Statement**

The task here is is to build a classifier that can classify for a given image as sober or mild drunk or drunk.  In order to train or test, we can consider all four, front, side etc. at once to classify whether drunk or sober. Detailed problem statement can be found [here](https://docs.google.com/document/d/1cFWjsTds1tODVCGt5Cg-ozIjxOQg3p6jWmyV1RcB4u4/edit)

The idea is to have a classifier which can be used in Real Life scenarios so you are free to make modifications / assumptions as long as these are valid in Real-Life scenarios.

## **Dataset**

The dataset contains IR images captured from a thermal camera for 50 different people. For each image, the class labels are provided in filenames. The labeling nomenclature is explained  along with the data capture process in the **“[readme](https://docs.google.com/document/d/1DqlKALYfs9uyE4kB-TXJ8tAN3tKjTu2JL_HXAoga-XY/edit)"**. 

Dataset contains images of 41 people in separate folders, taken from an IR sensor. For each person, images are taken in 4 conditions: sober (before drinking), 20 mins after drinking, 40 mins after drinking and 1hr after drinking 4 glasses of wine. For each condition and for each person, 4 images are taken: front face, side face, eyes, and hand palm.

**Dataset link - [SOBER  -  DRUNK   DATABASE](https://drive.google.com/drive/folders/1P1UG36IzvN0QVntn3t2atph215QU_sG1)**

## **Data Pre-processing**

**[data Pre-processing Notebook](https://colab.research.google.com/drive/1WDFH_bhImL9oo2-dK910kyuioMmVXKCt?usp=sharing)**

## **Colab Notebook study**

Below are the note book links conatining the extensive study regarding drunk state detection using several approaches.

1. **Deep_Learning_for_Binary_Drunks_Detection_with_Infrared_Camera_v2(Sober+3).ipynb**
* info: main notebook contains best model( custom base model), binary classification(sober state or drunk)
* [colab link](https://colab.research.google.com/drive/1uNglSHg5TjJ884sgD3dYqpB-B2NQJECP?usp=sharing)

2. **Data_Pre-processsing_for_Binary_Drunks_Detection_with_Infrared_Camera.ipynb**
* info: study regarding data preprocessing is done here
* [colab link](https://colab.research.google.com/drive/1WDFH_bhImL9oo2-dK910kyuioMmVXKCt?usp=sharing)

3. **Deep_Learning_for_Binary_Drunks_Detection_with_Infrared_Camera_v2(Sober+Drunk_state_3).ipynb**
* info: binary classfication experiements regarding (sober state+drunk state 3)
* [colab link](https://colab.research.google.com/drive/1Luua0oK82Qd4XSx08n5NVQHCqf0LDhoW?usp=sharing)

4. **Deep_Learning_for_Multi-Class_Drunks_Detection_with_Infrared_Camera_v2.ipynb**
* info: multi class/label classification
* [colab link](https://colab.research.google.com/drive/1HhpXdmf9l0QtHBZDQpJFlQQS2sXsGY4l?usp=sharing)

5. **Deep_Learning_for_Binary_Drunks_Detection_with_Infrared_Camera_v2(Sober+3_Drunks)_inverted.ipynb**
* info: same as 1., but image is inverted(result very poor)
* [colab link](https://colab.research.google.com/drive/1kfk0dv-E1aW9Lautx7-MP-Non0W8KIrw?usp=sharing)


## **Reference**

* [Deep Learning Technology for Drunks Detection with Infrared Camera](https://ieeexplore.ieee.org/document/9165395)
* [OpenCV Colormap](https://docs.opencv.org/3.4/d3/d50/group__imgproc__colormap.html)
* [Flir Image Extractor](https://pypi.org/project/flirimageextractor/)
* [Classification on imbalanced data](https://www.tensorflow.org/tutorials/structured_data/imbalanced_data)
* [Analyzing data augmentation for image classification](https://towardsdatascience.com/analyzing-data-augmentation-for-image-classification-3ed30aa61411)
* [How we utilized gamma correction for increasing our training data ?](https://medium.com/giscle/how-we-utilized-gamma-correction-for-increasing-our-training-data-47c16a040adc)
