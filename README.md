# Dyslexia Detection

>  an affordable and efficient way to detect if a kid has high risk of Dyslexia to provide suitable care for kids in early stages. 

## Features
- screening the movement of the eye using a normal webcam
- analyze the duration  and frequency of reader fixations. 
- show if the reader is a potential Dyslexia patient in real-time.  

## Tech
Built in C++ with OpenCV, eyeLike and matplotlib-c++

## Requirements
* [OpenCV](https://opencv.org/)
* Cmake

## Installation
1. Download the repository (project) from the download section or clone it using the following command:
   ```shell
   git clone https://github.com/a-elrawy/dyslexia-detection
   cd dyslexia-detection/
   ```
2. Build and run the app by running the cmake command inside the project folder:
   ```shell
   mkdir build
   cd build
   cmake ../
   make
   ./bin/eyeLike
   ```
