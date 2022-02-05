<h1 align="center">Face Mask Detection by S.R.</h1>

- - -

<div align= "center">
  <h4>Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and OpenCV in order to detect face masks in real-time webcam feed.</h4>
</div>

- - -

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## Dataset
This dataset consists of __3835 images__ belonging to two classes:
*	__with_mask: 1916 images__
*	__without_mask: 1919 images__

The images used were real images of faces wearing masks. The images were collected from the following sources:

* __Bing Search API__ ([See Python script](https://github.com/Hott-J/Face-Mask-Detection/blob/master/search.py))
* __Kaggle datasets__ 
* __RMFD dataset__ ([See here](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset))

<br/>

## How to use

1. TRAIN DATASET:
```
$ python3 train_mask_detector.py --dataset dataset
```

2. JPG IMAGES:
```
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. MP4 VIDEO:
```
$ python3 detect_mask_video.py 
```
4. FULL APPLICATION (WIP):
```
$ streamlit run app.py 
```
5. REAL-TIME WEBCAM:
```
$ streamlit run detect_mask_webcam.py
```
<br/>

## Results

## This Model gives 93% accuracy for Face Mask Detection after training with <code>tensorflow-gpu==2.0.0</code>

![](https://github.com/chandrikadeb7/Face-Mask-Detection/blob/master/Readme_images/Screenshot%202020-06-01%20at%209.48.27%20PM.png)

## Tech & Framework

- [OpenCV](https://opencv.org/)
- [OpenH264](https://https://github.com/cisco/openh264)
- [Face detector Model](https://www.pyimagesearch.com/2020/05/04/covid-19-face-mask-detector-with-opencv-keras-tensorflow-and-deep-learning/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)
- [Streamlit](https://www.streamlit.io/)

<br/>

## Streamlit Free Services
Streamlit is an open-source Python library that makes it easy to build beautiful custom web-apps for machine learning and data science. To use it, just pip install streamlit , then import it, write a couple lines of code, and run your script with streamlit run [filename] <br/>
<p align="center"><img src="https://user-images.githubusercontent.com/47052106/90765856-a46b1e00-e325-11ea-9b2a-549fb4f96151.png" width="400" height="200"></p>

<br/>