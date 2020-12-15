# KNU_development-of-face-mask-detector

* reference
  - Yolo : https://pjreddie.com/darknet/yolo/
    - AlexeyAB Darknet : https://github.com/AlexeyAB
* dependencies 
  - OpenCV : https://opencv.org/
  - Nvidia Cuda : https://developer.nvidia.com/cuda-toolkit
    - check your compatible version : https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html
  - cuDNN : https://developer.nvidia.com/cuDNN
 
  <you need WebCam for input video, if your device do not have WebCam, You can use DroidCam>
   -  DroidCam : https://www.dev47apps.com/
* How to execute  
  0. using 'git lfs pull' , you must 'git lfs pull'. (anyway. you must put 'yolov3_final.weights' file in 'build' directory)
  1. open terminal, and go to 'build' directory 
  2. type 'darknet detector demo obj.data yolov3.cfg yolov3_final.weights' to execute detector
