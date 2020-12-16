# KNU_development-of-face-mask-detector

* reference
  - Yolo : https://pjreddie.com/darknet/yolo/
    - AlexeyAB Darknet : https://github.com/AlexeyAB
    
* dependencies 
  1. OS : Windows
  2. 'yolo_cpp_dll.dll' library
      - you can make this library at 'AlexeyAB Darknet'
         - OpenCV : https://opencv.org/
         - Nvidia Cuda : https://developer.nvidia.com/cuda-toolkit
           - check your compatible version : https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html
         - Nvidia cuDNN : https://developer.nvidia.com/cuDNN
      - pre-compiled library('yolo_cpp_dll.dll') in 'lib' directory is compiled with - 'opencv : 3.4.0' , 'CUDA : 10.1(for GPU version)'
  3. WebCam
      - if your device does not have WebCam, You can use DroidCam
        - DroidCam : https://www.dev47apps.com
        
* How to execute
  - put the followings in the same directory
    - all contents of 'build'
    - all contents of 'execute_environment'
    - 'yolo_cpp_dll', you can use pre-compiled library in 'lib/GPU' or 'lib/NO_GPU'
  - execute 'yolo_console_dll.exe'
    - in the CMD you can give arguments 
       - "yolo_console_dll <threshhold(0~1)> <log_file location>", default log_file is "result.txt"
       - "yolo_console_dll <threshhold(0~1)>"
  
* How to compile 'src/yolo_console_dll.cpp'  
  - this code is Revision of 'darknet/src/yolo_console_dll.cpp' in 'AlexeyAB Darknet'
  - convert that code, and build with Visual Studio Solution 'darknet/build/darknet/yolo_console_dll.sln' in 'AlexeyAB Darknet'
  - Please refer to 'https://github.com/AlexeyAB/darknet' for detailed information
