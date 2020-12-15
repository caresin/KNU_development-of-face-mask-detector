# KNU_development-of-face-mask-detector

* reference
  - Yolo : https://pjreddie.com/darknet/yolo/
    - AlexeyAB Darknet : https://github.com/AlexeyAB
* dependencies 
  - OpenCV : https://opencv.org/
  - Nvidia Cuda : https://developer.nvidia.com/cuda-toolkit
    - check your compatible version : https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html
  - cuDNN : https://developer.nvidia.com/cuDNN
 
  <you need WebCam for input video, if your device does not have WebCam, You can use DroidCam>
   -  DroidCam : https://www.dev47apps.com/
* How to execute  
  1. Clone this repository. 'build/yolov3_final.weights' file has uploaded by 'git lfs'. so you must pull by 'git lfs pull', or download directly
  2. Open terminal, and go to 'build' directory 
  3. Prepare your WebCam.
  4. Execute detector by 'darknet detector demo obj.data yolov3.cfg yolov3_final.weights'
