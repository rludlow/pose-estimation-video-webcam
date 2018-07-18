# 2d Pose Estimation for Video and Realtime Webcam Streams

This repo offers demos of 2d pose estimation in videos and live camera streams via a modified implementation of [Michael Faber's](https://github.com/michalfaber) [Keras Version](https://github.com/michalfaber/keras_Realtime_Multi-Person_Pose_Estimation) of [Zhe Cao](https://github.com/ZheC) et al's [Realtime_Multi-Person_Pose_Estimation](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation).


## Introduction


## Results

## How it Works
The key files are modifications of demo_image.py from the original repository.
- demo_video.py simply reads a video, analyzes each frame, and outputs a video with the joint estimations overlayed and a .npy file of the estimated joint coordinates per frame.
- demo_camera.py reads from your computer's built-in camera and uses various techniques to pare down the size of the image to be analyzed, the depth of the analysis by the neural network, and the frequency of analysis. Additional details on how it functions and how to tune the parameters to make it work for you are [##TO-DO available here].

## Required Libraries
1. [Keras](https://keras.io/)
2. [TensorFlow]()
3. [OpenCV]()
