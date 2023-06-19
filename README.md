
![header](https://capsule-render.vercel.app/api?type=Waving&color=auto&animation=fadeIn&height=160&section=header&text=Morse%20Code%20Translator&fontSize=60)
# 

## Overview
The project involves using computer vision techniques provided by OpenCV to process images or video frames containing Morse code signals. The application applies image processing operations to enhance the Morse code signals, such as thresholding, morphological operations, and contour detection. These techniques help isolate and extract the Morse code symbols from the image.

## Getting Started

### Prerequisites
Install 
[Python3](https://www.python.org/downloads/)
[opencv V3.0+](https://pypi.org/project/opencv-python/)
[NumPy V1.0+](https://pypi.org/project/numpy/)

### Installation

### Usage
First clone this project
```sh
git clone https://github.com/ravdsn/morse-code-translator.git
cd morse-code-translator 
```
Then, run morseCodeTranslator.py 
```sh
python3 morseCodeTranslator.py 
```

## Screenshots

#### 1. Input image
![](wiki/outputims/Original.jpg)

#### 2. Crop paper part that contain morse codes
![](wiki/outputims/Outline.jpg) 
![](wiki/outputims/birdeyeImage.jpg)

#### 3. Output
![](wiki/outputims/output.png)


## :warning: Warning 
Gives some error with opencv V4.0+
